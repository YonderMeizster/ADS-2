# Двочиное дерево в виде массива

Существует возможность представления двоичного дерева не только как
скопления ссылающихся на другие ноды нод, но также и в виде массива.

Размер массива, предназначенный для хранения двоичного дерева
вычисляется по следующей формуле: 2 ** (depth + 1) - 1.

В таком случае некий индекс I является индексом- родительского узла для
левого потомка с индексом (I * 2 + 1) и правого потомка с индексом (I *
2 - 1)