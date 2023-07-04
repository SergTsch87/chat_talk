# chat_talk
Chat app with different chat rooms

**Requirements**

**General**

Додаток, де будь-хто може приєднатися до обговорення різних тем. Є список чатів (тем).
Користувачі можуть приєднатися, використовуючи лише ім'я користувача (авторизація не потрібна). 

Має бути перевірка на людину.

Одночасно можуть спілкуватися в чаті більше 2 користувачів. Ви не можете використовувати бібліотеки чатів у цьому проєкті. Необхідний функціонал: 

- повідомлення з’являються миттєво; 

- власні повідомлення з’являються на другій відкритій вкладці; - під питанням

- екран чату має завжди прокручуватися до останнього повідомлення; 

- користувачі мають бачити, коли хтось набирає текст; 

- відображати дату й час біля кожного повідомлення;

 - ім'я користувача залишається після вкладки, що закривається. 

додаток в веб версії, яка адаптована під мобайл.

фільтрація чатів за актуальністю (датою останнього повідомлення) та кількістю повідомлень.

аунтифікація з вводом імейла

назви каналів мають бути унікальними 

назва проєкту - вирішуємо голосуванням 

мова - англійська

автор каналу може додати фото каналу

у кожного каналу є опис

свої канали (канали які створив користувач) виділяються кольором







**Додатковий функціонал:**
- створювати різні кімнати за інтересами;
- надіслати приватне повідомлення, показати непрочитані повідомлення;
- мати можливість відповісти на повідомленя іншого користувача в чаті.

Орієнтовний термін реалізації проєкту - 4 місяці. Фінальна точка часу залежить від команди. картинка юзера за допомогою граватар 


**Технології:**
**frontend:** React native, Redux,
**backend:** Pyton, Web Sockets або Node 


**Wireframes**

https://cacoo.com/diagrams/7EXMTF5Ob6Q2So3U/612A3 


**User Stories**

As a user I want to login by emailAcceptance criteria:- email is stored as username- if user entered with the same email second time - he sees his channels and messages

As a user I want to see all channels on the Home ScreenAcceptance criteria:- channels can scroll- each channel has photo (or empty space for it), name of the channel, author, description and number of messages - loading is paginated (depends on how many channels fit on the user's screen). Сhannels are loaded and appear below as a continuation of the list- the description of the channel is given (a number of) terms, all the rest are hidden, and at the end of the visible text "..."

As a user I want to search channels by nameAcceptance criteria:- the search starts after entering 3 letters- all options appear 1 second after user finishes typing (no more than ..)

As a user I want to filter channels on Home ScreenAcceptance criteria:- parameters: the date of last message, the number of messages in channel

As a user I want to create new channelAcceptance criteria:- open Create New Channel screen- CNC screen contains field for entering a name- name no more then 30 characters- field for entering a description - description no more then 120 characters- the possibility to add a photo - (photo restrictions)- “create channel” button - create channel button transports user to Channel Screen

As a user I want to see picture, name, author and full description on Channel ScreenAcceptance criteria:- everything besides name hides while scrolling - 

As a user I want to see messages in Channel ScreenAcceptance criteria: - my messages are on the right- others messages are on the left- above the message username (email)- date the message was sent next to each message- picture, description and author hides during scrolling, only name is visible

As a user I want to write new message to the channelAcceptance criteria- on mobile version keyboard appears - picture, description and author hides , only name is visible- the input field increases according to the amount of text, but no more then 9 lines- the scroll starts from line 10- user can scroll chat during typing the message 

As a user I want to sent my messageAcceptance criteria- message appears immediately in chat

As a user I want to see My Page with all channels I’ve created Acceptance criteria- list of channels with picture, name and description - scroll- pagination - channels are loaded and appear below as a continuation of the list





As a user I want to login by emailAcceptance criteria:- email is stored as username- if user entered with the same email second time - he sees his channels and messages

As a user I want to see all channels on the Home ScreenAcceptance criteria:- channels can scroll- each channel has photo (or empty space for it), name of the channel, author, description and number of messages - loading is paginated (depends on how many channels fit on the user's screen). Сhannels are loaded and appear below as a continuation of the list- the description of the channel is given (a number of) terms, all the rest are hidden, and at the end of the visible text "..."

As a user I want to search channels by nameAcceptance criteria:- the search starts after entering 3 letters- all options appear 1 second after user finishes typing (no more than ..)

As a user I want to filter channels on Home ScreenAcceptance criteria:- parameters: the date of last message, the number of messages in channel

As a user I want to create new channelAcceptance criteria:- open Create New Channel screen- CNC screen contains field for entering a name- name no more then 30 characters- field for entering a description - description no more then 120 characters- the possibility to add a photo - (photo restrictions)- “create channel” button - create channel button transports user to Channel Screen

As a user I want to see picture, name, author and full description on Channel ScreenAcceptance criteria:- everything besides name hides while scrolling 

As a user I want to see messages in Channel ScreenAcceptance criteria: - my messages are on the right- others messages are on the left- above the message username (email)- date the message was sent next to each message- picture, description and author hides during scrolling, only name is visible

As a user I want to write new message to the channelAcceptance criteria- on mobile version keyboard appears - picture, description and author hides , only name is visible- the input field increases according to the amount of text, but no more then 9 lines- the scroll starts from line 10- user can scroll chat during typing the message 

As a user I want to sent my messageAcceptance criteria- message appears immediately in chat

As a user I want to see My Page with all channels I’ve created Acceptance criteria- list of channels with picture, name and description - scroll- pagination - channels are loaded and appear below as a continuation of the list
