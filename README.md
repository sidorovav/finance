# Проект 1
```mermaid
graph TB
         A[13,032] --> |Accept John's Offer| B[12,000]
         A ==> |Reject John's Offer |C(($13,032))
         C --> |Offer from Vanessa 0.6| D[$14,000]
         D ==> |Accept Vanessa's Offer| E[$14,000]
         D --> |Reject Vanessa's Offer| F(($11,580))
         C --> |No Offer from Vanessa 0.4| G(($11,580))
         G --> |Salary 1 0.05| H[$21,600]
         G --> |Salary 2 0.25| I[$16,800]
         G --> |Salary 3 0.40| J[$12,800]
         G --> |Salary 4 0.25| K[$6,000]
         G --> |Salary 5 0.05| L[$0]
         F --> |Salary 1 0.05| M[$21,600]
         F --> |Salary 2 0.25| N[$16,800]
         F --> |Salary 3 0.40| O[$12,800]
         F --> |Salary 4 0.25| P[$6,000]
         F --> |Salary 5 0.05| Q[$0]
```
# Проект 2
```mermaid
graph TB

%% Определение цвета %%
classDef blue fill:green, stroke:red, stroke-width:2px,color:#fff
classDef red fill:red, stroke:red, stroke-width:2px,color:#fff

A[Square Rect] -- Следствие --> B((Задача RR-5865))
A --> C(Round Rect)
B --> D{Rhdddddombus}
C --> D 
%% Коментарий %%
B <==> X[Dedline] ---> T[Time]
T ---> F[Forest]
T----> |Обратная зависимость| B

%% цвет %%
B:::blue
C:::blue
T:::red
%% ссылки
click B "https://deskalertsdev.atlassian.net/browse/RR-5865"
```
