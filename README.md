## `$ whoami`

```c
struct Developer {
    const char* name;
    const char* role;
    const char* currentlyLearning[4];
};

struct Developer gabi = {
    .name = "Gabriella de Lima",
    .role = "dev in progress",
    .currentlyLearning = {
        "c",
        "framework django",
        "lógica",
        "IHC"
    },
};
