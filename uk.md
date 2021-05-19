---
layout: app
title: WebCrypt &mdash; Шифрування повідомлень онлайн
nav:
    toggle: Сховати/Показати навігацію
    encryption: Шифрування
    decryption: Розшифрування
    about: Про проєкт
label:
    info: Підказка
button:
    encrypt_new: Зашифрувати нове повідомлення
placeholder:
    password: Гасло (пароль)

encrypt:
    title: Шифровання
    placeholder: Повідомлення для шифрування
    weak: Слабкий
    mediocre: Нормальний
    strong: Сильний
    button: Зашифрувати
    hint: Підказка гасла (паролю)
    config:
        add_hint: Додати підказку для гасла
        remove_hint: Видалити підказку для гасла

encrypt_done:
    title: Ваше повідомлення було зашифроване
    link_text: Скопіюйте і відправте це посилання.  Для безпеки, пароль не відсилайте тим же каналом зв'язку.
    textarea_text: Скопіюйте і відправте цей текст. Для безпеки, пароль не відсилайте тим же каналом зв'язку.

decrypt:
    title: Расшифрування
    placeholder: Повідомлення для розшифрування
    button: Розшифрувати

decrypt_done:
    title: Повідомлення було зашифровано

modal:
    decrypt:
        title: Введіте гасло (пароль)
        button: Розшифрувати
    decrypt_error:
        error: Неможливо розшифрувати повідомлення.
        info: Можливо, воно пошкоджене або введено некоректний пароль.
        button: Спробуйте ще раз

config:
    title: Додатково
    save: Зберегти
    reset: Скинути

about:
    title: О WebCrypt
    body: |
        <p>
            <strong>WebCrypt</strong> эце відкрите програмне забезпечення для шифрування повідомлень прямо в браузері.
        </p>

        <p>
            WebCrypt це повністю безпечний спосіб передачі конфіденційних даних, так як ніякі ваші дані не зберігаються на сервері
            і навіть не передаються на сервер. Весь процес шифрування відбувається прямо в браузері.
        </p>

        <p>
           Початковий код WebCrypt відкритий і опублікований під ліцензією <a href="https://www.gnu.org/licenses/gpl.html">GNU GPL</a>.
           Він ґрунтується на чудовій бібліотеці Стенфордського університету <a href="http://bitwiseshiftleft.github.io/sjcl/">Stanford Javascript Crypto
            Library</a>
            і розміщується на <a href="https://github.com/elfet/webcrypt">GitHub</a>.      
        </p>

info:
    features:
        open_source: відкрите програмне забезпечення
        no_store: нічого не зберігається на сервері
        no_trans: нічого не передається на сервер
---
