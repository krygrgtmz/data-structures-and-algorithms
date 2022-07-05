# Merge Sort Projesi

## **[16,21,11,8,12,22]** -> Merge Sort
1. Yukarıdaki dizinin merge sort türüne göre aşamalarını yazınız.
2. Yukarıdaki dizinin Big-O gösterimini yazınız.
---
### 1. Merge Sort Aşamaları

| İşlem | Dizi |
| ---   | ---  |
| Start | [16,21,11,8,12,22] |
| Divide | [16,21,11] - [8,12,22] |
| Divide | [16] - [21,11] - [8] - [12,22] |
| Divide | [16] - [21] - [11] - [8] - [12] - [22] |
| Merge | [16] - [11,21] - [8] - [12,22] |
| Merge | [11,16,21] - [8,12,22] |
| Merge | [8,11,12,16,21,22] |
---
### 2. Big-O Gösterimi
- Time Complexity: n*logn
- Big-O Notasyonu: O(n*logn)
- **n=6 --> O(6log6)**
