# Java Building Blocks

###### Lesson Goals

1. Get practice with IDE.
2. Learn basic Java syntax.
3. Implement simple application.

We will move through three simple parts.

1. Create new project.

   Open Intellij IDEA (Icon should be somewhere on Desktop)

   Follow tips on the pics

![](https://github.com/akhambir/JavaBuildingBlocks/blob/master/resources/img/icon_1.png)

![](https://github.com/akhambir/JavaBuildingBlocks/blob/master/resources/img/icon_9.png)

![](https://github.com/akhambir/JavaBuildingBlocks/blob/master/resources/img/icon_10.png)

![](https://github.com/akhambir/JavaBuildingBlocks/blob/master/resources/img/icon_2.png)

Double check project SDK

![](https://github.com/akhambir/JavaBuildingBlocks/blob/master/resources/img/icon_7.png)

![](https://github.com/akhambir/JavaBuildingBlocks/blob/master/resources/img/icon_4.png)

Create base package.

![](https://github.com/akhambir/JavaBuildingBlocks/blob/master/resources/img/icon_8.png)

Using "." you can create few packages in single operation.

![](https://github.com/akhambir/JavaBuildingBlocks/blob/master/resources/img/icon_3.png)

Create new Class.

![](https://github.com/akhambir/JavaBuildingBlocks/blob/master/resources/img/icon_5.png)

UseCamelCaseForClassNamesStartingFromLeadCapitalLetter

![](https://github.com/akhambir/JavaBuildingBlocks/blob/master/resources/img/icon_6.png)


2. Learn some Java syntax.

   Learn variables by creating few of them.

   Think about variables like about boxes with different size and forms.
   Some of them are good for storing one things, but not good for others and vice versa.

    ```java
        int integerNumber = 5;

        /**
        * This is variable. This one is very good for integer values.
        * Key word is "int" which is part of Java syntax.
        * It's name "integerNumber" which is chosen by creator and can be user for calling it again
        * For example:
        */

        int imNewInteger = integerNumber + integerNumber;

        /**
        * The result value inside "imNewInteger" will be 10.
        * As you remember value stored in "integerNumber" variable was 5.
        *
        * We can store and change values inside variables using "=" symbol.
        * For example:
        */

        integerNumber = imNewInteger;

        /**
        * For this operation we dont need key word "int" in the beginning of the string.
        * Both variables already created so we just reusing them by calling their names.
        *
        * The result was 10 inside both variables. 
        */

    ```