# Lab 6 - my answers
Name: David Amutebi - Admission number: 227625

## 1. Why does PHP check the member number again?
It prevents those who skipped the JavaScript check by turning off JavaScript, thus preventing them from entering bad data in the database and causing confusion.

## 2. What do the letters 'issd' in bind_param stand for, and which value does each go with?
i stands for integer, and 2 is the value for the farmer id. s stands for string, which is text, for the date and the session, which is Morning in this case. d stands for double, which is the number of litres, and it can also be written in decimal.

## 3. Why is Delete a small form sent by post, while Edit is a link?
Delete is a form because it only acts when someone deliberately presses it, and Edit is a link because it is safe and clicking it changes nothing but shows the edit page, which will only change when the changes are saved.

## 4. Someone opens deliveries.php?date=' OR '1'='1 on my site. What happens, and why does my prepared statement not run it as SQL?
It does not run in MySQL because the SQL is read first, then the text is dropped in as a plain value, so the page brings nothing back.
