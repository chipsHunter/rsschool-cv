# ***Anastasia Hvorostova***
![image](https://github.com/chipsHunter/rsschool-cv/assets/130827200/34f8d103-cb48-4f04-83d6-214369fee2a6)
**********************************************
## **CONTACTS**:
* +375 (29) 996 41-74
* E-mail: hvorostok8@gmail.com
* Discord:
* Telegram:  https://t.me/skelletonchik
* GitHub:    [chipsHunter](https://github.com/chipsHunter)
**********************************************
## **BRIEFLY**: 
I'm a student of BSIUR, future systems engineer. 
I'm highly motivated and disciplined person, who can set goal and achieve it. 
My aim for near 5 years in Uni find field I'd like to self-develop in and become a programmer with strong skills in this area.
I made self-development part of everyday life. Every day I try to practice my coding skills or learn something.
**********************************************
## **COURSE**:
* Completed course for Java beginners in 2022. 
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
* Uni's course of C
**********************************************
## **SKILLS**:
* Java:
* C
* HTML (basic skills)
**********************************************
## **LANGUAGES**:
* Russian (native)
* Belarusian (native)
* English (B1)
**********************************************
## **CODE EXAMPLE**:
* Java. _Return sum of all nums below entered can be devided into 3 and 5_ 
```
public class Solution {

  public int solution(int number) {
    --number;
    if(number <= 0)
      return 0;
    else {
      if((number % 3 == 0) || (number % 5 == 0) )
        return number + solution(number);
      else return solution(number);
      }
  }
}
```
* C. _Append node in binary tree_
```
struct TREE *insert_node(struct TREE *root, int value) {
    // если дерево пустое, создаем новый узел с заданным значением
    if (root == NULL) {
        root = (struct TREE*)malloc(sizeof(struct TREE));
        root->value = value;
        root->leftChild = NULL;
        root->rightChild = NULL;
    }
    else {
        // если значение меньше значения корня, рекурсивно добавляем его в левое поддерево
        if (value < root->value) {
            root->leftChild = insert_node(root->leftChild, value);
        }
            // в противном случае, рекурсивно добавляем его в правое поддерево
        else {
            root->rightChild = insert_node(root->rightChild, value);
        }
    }
    return root;
}
```
