# Planejamento de teste

- data inicial e final != dia util

## Exemplos

### Tabela verdade

---------- | -------- | ------- | -------- |

Dt inicial | Dt final | Periodo | Resultado |

---------- | -------- | ------- | ----------- |

dia n util | dia util | < 3 | dt ini n é dia util

---------- | ------- | ---- | -------------- |

dia util | dia n util | < 3 | dt fim dia n util |

---------- | -------- | --- | -------------- |

dnu | dnu | < 3 | datas usadas n sao dias utils |

---------- | -------- | --- | -------------- |

du | du | > 3 | periodo esta fora |

---------- | -------- | --- | -------------- |

du | du | = 3 | periodo esta fora |

---------- | -------- | --- | -------------- |

### Escrita orientado a comportamento

Dado que eu informe a "data inicial"
E a "data final" com dia n util
Quando eu realizar a busca
Então verei a msg XPO

ou

Dado que eu informe uma das "datas inicial ou final"
Então verei a msg XPO

### Diagrama

<img src="diagrama.png" alt="diagrama">
