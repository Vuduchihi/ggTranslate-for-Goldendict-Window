# ggTranslate-for-Goldendict-Window
Các bạn dung Mac thì kéo xuống dưới có link tham khảo nhé!!!


Bước 1: Cài đặt python3: https://www.python.org/downloads/windows/

Chú ý: xem máy bạn bao nhiêu bit để tải bản phù hợp nhé!
 
Tham khảo cách cài đặt python: https://www.youtube.com/watch?v=ZTj2aPkaZPE 

Bước 2: https://github.com/xinebf/google-translate-for-goldendict/blob/master/google_translate.png

Bước 3: nhấn phím {Win} -> gõ "cmd" -> {Enter}

Bước 3.1: py -m pip --version

Bước 3.2: py -m pip install --upgrade pip

Bước 3.3: py -m pip install --user virtualenv

Bước 3.4: py -m venv env1

Bước 3.5: .\env1\Scripts\activate

Bước 3.6: py -m venv gtrans1

Bước 3.7: .\gtrans1\Scripts\activate

Bước 3.8: pip3 install google-translate-for-goldendict

Bước 3.9: deactivate

Bước 4: mở txt

Bước 4.1: python -m googletranslate vi %GDWORD%

Bước 4.2: C:\ -> User -> gtrans1 -> Scripts -> pythonw.exe -> copy path

Bước 4.3: thế vào chữ "python" ở bước 4.1 -> copy toàn bộ

Bước 5: mở Goldendict -> Edit -> Dictionaries -> Programs -> Add

Bước 5.1: mục Type chọn Html; Name: Google Translate; Command Line: Ctrl + v

LƯU Ý: nếu các bạn muốn từ đồng nghĩa, định nghĩa, ví dụ thì ở bước 4.1 các bạn thay từ -s... thành -m -d -e 

như này: python -m googletranslate vi %GDWORD% -m -d -e

-m              show synonyms

-d              show definitions

-e              show examples

Các bạn dùng Macbook thì kham khảo link này nhé: 

https://github.com/xinebf/google-translate-for-goldendict

https://www.youtube.com/watch?v=1opEeB9WLYU
