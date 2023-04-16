# Details

Rename this file in the format `yourRollNumber_solution.md` (example, `220000_solution.md`) and submit the solution in the Google form link provided 
*** https://forms.gle/RZtKpFcKfrWrYYxF9 ***


## Your zeroth approach below

Reasoning - %%% In the first challange at first I WSL following the given steps. Then I changed the type of array ved[] from int to char to execute the code.The output of the program stated "The answer of this challenge is output of "man" when run on the terminal, copy the exact output". Then I ran "man" on terminal and copied its output.  %%%

```
%%% What manual page do you want?
For example, try 'man man'. %%%
```

---

## Your first approach below (first.txt)

Reasoning - %%% For decrypting the code I wrote a code which shift all the characters by 11.


    int main() {
    #include <bits/stdc++.h>
    using namespace std;

    int main() {
        string input_str = "fgauww qgm vav ujsuc s jglslagf wfujqhlagf gf qgmj gof. Lzw xgddgoafy ak s udmw xgj lzw fwpl hmrrdw: UDSKK gx lzsl AFHML";
        int shift = 8;
        for (char& c : input_str) {
            if (c >= 'a' && c <= 'z') {
                c = 'a' + (c - 'a' + shift) % 26;
            } else if (c >= 'A' && c <= 'Z') {
                c = 'A' + (c - 'A' + shift) % 26;
            }
        }

        cout << input_str << endl;

        return 0;
    }
} %%%

```
%%% noicee you did crack a rotation encryption on your own. The following is a clue for the next puzzle: CLASS of that INPUT %%%
```

---

## Your second approach below (strings.txt)

Reasoning - %%% I found the file strings.txt from in the Lamp_Stack_task file by searching for it %%%

```
%%% "Lamp_Stack_Task\Lamp_Stack_task\question_mark\Lamp_Stack\1\5\0\3\strings.txt" %%%
```

---

## Your third approach below (fourth.zip)

Reasoning - %%% The password was eleven.txt which was the name of the file I which contained the string "8dc2evcCSSc4kUy" from strings.txt which had password marked against it. %%%

```
%%% DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r} %%%
```

---


- Name :Aditya Kumar Raj
- Roll :220067
- GitHub username:AdityaRajIITK
- Discord username:aditya_raj__07


## Do not tamper below this line

---

Q29yZSB0ZWFtIGtvIGZha2UgZG8=
