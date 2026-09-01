Collection (interface)
├── List – ordenada, permite duplicatas
│   ├── ArrayList – acesso rápido por índice O(1)
│   ├── LinkedList – inserção/remoção rápida no meio O(1)
│   └── Vector (legado, não usar)
├── Set – sem duplicatas
│   ├── HashSet – mais rápido, sem ordem
│   ├── LinkedHashSet – mantém ordem de inserção
│   └── TreeSet – ordenado naturalmente
└── Queue – FIFO
    ├── LinkedList
    ├── PriorityQueue – min-heap
    └── Deque (ArrayDeque) – pilha + fila

Map – chave → valor (não é Collection, mas faz parte do Java Collections Framework)
├── HashMap – mais rápido, sem ordem
├── LinkedHashMap – mantém ordem de inserção
├── TreeMap – ordenado por chave
└── Hashtable (legado, não usar)
