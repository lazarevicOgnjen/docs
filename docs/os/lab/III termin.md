**procesi**
---

<br>

> 🚨 **BITNO**

- novi proces dobijamo tako sto **dupliramo postojeci**
- korisitmo **fork**
- novi proces **nasledjuje sav kod i vrednosti promenljivih** od roditelja


<br>

**biblioteke**
---

```c
#include <sys/types.h>
#include <unistd.h>

```

**fork**
---

```c

pid_t fork(); // kreiramo novi proces

// provera koji se proces izvrsava
switch( cpid=fork() ){

  case -1:
    perror("funkcija fork nije uspela");
    exit(1);

  case 0: // izvrsava se proces dete
    continue_child();
    break;

  default: // izvrsava se proces roditelj
    continue_parent(cpid);

}

```








