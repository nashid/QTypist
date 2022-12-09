1

# QTypist

2

A tool to automatically generate the input text. It is like an intelligent typist writing correct input text according to different mobile app input scenarios.

3

​

4

We give source code (./source code/)

5

​

6

As shown in the following table, it is all our patterns.

7

​

8

<table>

9

    <tr>

10

        <td><b>Id</b></td>

11

        <td><b>Sample of linguistic patterns/rules</b></td>

12

        <td><b>Examples of linguistic patterns/rules</b></td>

13

    </tr>

14

    <tr>

15

        <td colspan = "3"><b>Patterns related to input widget: IWPn</b> </td>

16

    </tr>

17

    <tr>

18

        <td>1</td>

19

        <td>Please input < widget[n] >, the < widget[n] > is</td>

20

        <td>Please input game name, the game name is</td>

21

    </tr>

22

    <tr>

23

        <td>2</td>

24

        <td>Please input < widget[det+n] >, < widget[det+n] > is</td>

25

        <td>Please input your nickname, your nickname is</td>

26

    </tr>

27

    <tr>

28

        <td>3</td>

29

        <td>Please < widget[v+n] >, the < widget[n] > is</td>

30

        <td>Please search the food, the food is</td>

31

    </tr>

32

    <tr>

33

        <td>4</td>

34

        <td>Please < widget[v] > </td>

35

        <td>Please search </td>

36

    </tr>

37

    <tr>

38

        <td>5</td>

39

        <td>< widget[n] > + $[MASK]$ + < widget[n] ></td>

40

        <td>Your weight is [MASK] kg</td>

41

    </tr>

42

    <tr>

43

        <td>6</td>

44

        <td>< widget[n] > + $[MASK]$ </td>

45

        <td>Your age is [MASK]</td>
