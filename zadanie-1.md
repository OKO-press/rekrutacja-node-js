# Zadanie 1
Celem zadania jest napisanie funkcji w jezyku Node.js wraz z pełnym typowaniem Typescript.

**Input**: Funkcja otrzymuje Datę reprezentowaną za pomocą typu wbudowanego `Date` oraz status transakcji przekazany za pomocą typu `bool`.

**Output**: Funkcja zwraca nową datę reprezentującą datę w przyszłości.

**Logika**: Jeśli status transakcji jest `true` zwracana data powinna być miesiąc w przyszłość (zobacz przykłady). Jeśli status transakcji jest `false` zwracana data powinna być 5 dni w przyszłości (zobacz przykłady). 

**Przykład 1**:
Input: `2022-10-03T08:12:59Z, true`
Output: `2022-11-03T08:12:59Z`

**Przykład 2**:
Input: `2022-10-03T08:12:59Z, false`
Output: `2022-10-08T08:12:59Z`

**Przykład 3**:
Input: `2022-01-31T08:12:59Z, true`
Output: `2022-02-28T08:12:59Z`
