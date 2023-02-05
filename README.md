<img height="600em" src="https://inprogrammer.com/wp-content/uploads/2022/06/Image-for-introduction-to-python-10.jpg" alt="english" align = "center"/>


<img height="30em" src="https://raw.githubusercontent.com/anki-geo/ultimate-geography/a44a569a922e1d241517113e2917736af808eed7/src/media/flags/ug-flag-united_kingdom.svg" alt="english" align = "center"/>

# Rock Paper Scissors
Rock Paper Scissors game on Python


## Algorithm
- Import the random module
- Initialize the global variables for choices as a tuple of r, p, s, and computer score and player score as 0.
- Create a function for getting the player’s choice.
<pre>1. Inside the function get the input from the user.
2. Check if the input is valid, If yes then return the answer to the function call. If no, then return the function call so that it will again ask for input from the user.</pre>
- Create a function to return the computer’s choice as input from the random. choice function.
- Create a game function inside which we will check who scores the mount for the current game.
<pre>1. Call the player’s choice function and save the answer in a variable.
2. Call the computer choice function and save it in another variable.
3. Now, check if both the answers are the same, if so then print its a tie and no one gets a point.
4. Following are the scenarios where the player gets a point,
<pre>- Player choice- “r” computer choice- “s”
- Player choice- “s” computer choice- “p”
- Player choice- “p” computer choice- “r”</pre>
5. In all the other conditions computer scores a point.
6. Now, print both the points to the user.</pre>
- Now, in our main part of the program, we need to write a welcome message.
- Call the game function 4 times for running the game for 4 rounds.
- Ask the user if the user wants to continue/ reset and continue/quit.
<pre>1. If the user wants to continue repeat step 7.
2. If the user wants to reset and continue re-declare the variables for player score and computer score to zero and repeat step 7
3. If the player wants to quit you can print thank you for playing and exit the game.</pre>

<img height="30em" src="https://raw.githubusercontent.com/anki-geo/ultimate-geography/a44a569a922e1d241517113e2917736af808eed7/src/media/flags/ug-flag-russia.svg" alt="russian" align = "center"/>

# Камень,Ножницы,Бумага
Игра Камень,Ножницы,Бумага на Python


## Алгоритм
- Импорт случайного модуля
- Инициализируйте глобальные переменные для выбора как кортеж r, p, s, а также счет компьютера и счет игрока как 0.
- Создайте функцию для получения выбора игрока.
<pre>1. Внутри функции получите ввод от пользователя. 
2. Проверьте правильность ввода. Если да, то верните ответ на вызов функции. Если нет, верните вызов функции, чтобы она снова запросила ввод от пользователя.</pre>
- Создайте функцию, возвращающую выбор компьютера в качестве входных данных из случайного числа. функция выбора.
- Создадим игровую функцию, внутри которой будем проверять, кто победил в текущей игре.
<pre>1. Вызовите функцию выбора игрока и сохраните ответ в переменной.
2. Вызовите функцию выбора компьютера и сохраните ее в другой переменной.
3. Теперь проверьте, совпадают ли оба ответа, если да, то выведите ничью, и никто не получит очко.
4. Ниже приведены сценарии, в которых игрок получает очко,
<pre>- Выбор игрока- «r» выбор компьютера- «s»
- Выбор игрока- «s» выбор компьютера- «p»
- Выбор игрока- «p» выбор компьютера- «r» </pre>
5. Во всех остальных условиях компьютер получает балл.
6. Теперь выведите обе точки пользователю. </pre>
- Теперь в нашей основной части программы нам нужно написать приветственное сообщение.
- Вызовите функцию игры 4 раза, чтобы запустить игру на 4 раунда.
- Спросите пользователя, хочет ли он продолжить/сбросить и продолжить/выйти.
<pre>1. Если пользователь хочет продолжить, повторите шаг 7.
2. Если пользователь хочет сбросить и продолжить, повторно объявите переменные для счета игрока и счета компьютера равными нулю и повторите шаг 7.
3. Если игрок хочет выйти, вы можете поблагодарить за игру и выйти из игры.</pre>
