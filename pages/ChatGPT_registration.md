---
title: Как зарегистрироваться в ChatGPT из России?
description: Инструкция по регистрации в ChatGPT из России
---
# Как зарегистрироваться в ChatGPT из России?

Почему для регистрации в ChatGPT нужна отдельная инструкция? OpenAI, создатели этого бота, заблокировали доступ для жителей некоторых стран, в том числе для жителей России. Не будем вдаваться в причины этого решения, благо все же выход для соотечественников есть. И я поведаю вам, как можно воспользоваться большим потенциалом ChatGPT ~~без регистрации и СМС~~.

![ChatGPT_website](/chatgpt_manual/images/ChatGPT_registration/ChatGPT_website.png)

Если попробовать зарегистрироваться на [сайте](https://chat.openai.com/chat) с территории России, то в 100% случаев мы увидим такое окошко снизу. OpeanAI не позволяет зарегистрироваться с российским IP.

![OpenAI_API_not_available](/chatgpt_manual/images/ChatGPT_registration/OpenAI_API_not_available.png)

Но если обойти ограничение и зайти на сайт под VPN, то зарегистрироваться все равно не получится, так как требуется не российский номер телефона.

![OpenAI_API_wrong_russian_number](/chatgpt_manual/images/ChatGPT_registration/OpenAI_API_wrong_russian_number.png)

Ниже я поведаю, как решить эти две проблемы.

**Инструкция, как получить доступ к ChatGPT + сделать ярлык на рабочий стол**

1. скачать [Google Chrome Portable](https://portableapps.com/apps/internet/google_chrome_portable) и установить.

2. открыть Google Chrome Portable и поставить бесплатное расширение [Adguard VPN](https://chrome.google.com/webstore/detail/adguard-vpn-—-free-secure/hhdobjgopfphlmjbmnpglhfcgppchgje?hl=ru) для обхода блокировки по VPN. Можно выбрать любое другое бесплатное VPN расширение.

3. зарегистрироваться в этом расширении. Для этого нажмите на значок пазла в верхнем правом углу браузера. Нажмите "Закрепить", что расширение отобразилось рядом со значком пазла.
   ![adguard_enter](/chatgpt_manual/images/ChatGPT_registration/adguard_in_chrome.png)

   Нажмите на значок расширения рядом с пазлом, зарегистрируйтесь в Adguard VPN. В конце этого этапа у вас должна в конце быть следующая картинка. Не выключайте VPN, при регистрации необходимо иметь IP адрес другой страны.
   ![adguard_login](/chatgpt_manual/images/ChatGPT_registration/adguard_login.png)

4. зайти на сайт [ChatGPT](https://chat.openai.com/chat).

   ![ChatGPT_login](/chatgpt_manual/images/ChatGPT_registration/ChatGPT_login.png)

5. зарегистрироваться (sign up) на сайте, ввести своё имя и фамилию.

6. мы дошли до второй проблемы — нужен не российский номер телефона для финального шага регистрации. Регистрируемся на [sms-man.ru](https://sms-man.ru/) для получения одного  СМС для регистрации.

7. После регистрации на [sms-man.ru](https://sms-man.ru/) выбираем страну "США" и сервис "OpeanAI", покупаем. Перед этим не забудьте пополнить счет на сайте через Qiwi.

   ![sms_man_USA_OpenAI](/chatgpt_manual/images/ChatGPT_registration/sms_man_USA_OpenAI.png)

8. Указываем этот номер телефон на сайте при регистрации в OpenAI. Не забудьте выбрать код страны +1 (USA). Чуть позже на номер телефона придет смс, её можно увидеть на сайте.

   ![sms_man_USA_OpenAI](/chatgpt_manual/images/ChatGPT_registration/sms_man_USA_OpenAI_SMS.png)
   В некоторых случаях смс может не прийти, попробуйте взять новый номер.

9. Ввести этот номер из сообщения для завершения регистрации.

10. Авторизоваться на сайте при включенном VPN.

11. Теперь можно выключить VPN: он был нужен только для регистрации и авторизации, после авторизации пользоваться сайтом можно с российским IP-адресом (то есть без VPN).

12. В качестве финального шага [адрес ChatGPT](https://chat.openai.com/chat) можно превратить в ярлык на рабочем столе. Для этого нажимаем на три точки в правом верхнем углу браузера, выбираем "Дополнительные инструменты — Создать ярлык".
    ![ChatGPT_thumbnail_creation](/chatgpt_manual/images/ChatGPT_registration/ChatGPT_thumbnail_creation.png)
    Нажмите на галочку "Открыть в отдельном окне". Нажимаем кнопку "Создать".
    ![image-20230225123616061](/chatgpt_manual/images/ChatGPT_registration/ChatGPT_thumbnail_creation_2.png)

13. Теперь через ярлык на рабочем столе можно получить доступ к ChatGPT как к отдельную приложению, а не вкладке в браузере.

    ![ChatGPT_thumbnail](/chatgpt_manual/images/ChatGPT_registration/ChatGPT_thumbnail.png)

14. Вы прекрасны, доступ к ChatGPT у вас есть!

Теперь вы можете начать пользоваться ChatGPT. А помогут вам эти советы:

- [Как пользоваться ChatGPT](/chatgpt_manual/pages/ChatGPT_usage)
- [Советы и примеры по ChatGPT для IT-специалистов](/chatgpt_manual/pages/ChatGPT_IT_usage)

Кроме этого можно использовать ChatGPT с помощью [API key](https://platform.openai.com/account/api-keys). К примеру, можно внедрить чатбота в Visual Studio Code через расширение [CodeGPT](https://code-gpt-docs.vercel.app/), чтобы задавать ему вопросы по коду и работе.