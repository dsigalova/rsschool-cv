# Daria Sigalova
## Contact information

**E-mail:** d.sigalova@gmail.com

**Telegram:** [dariasigalova](https://t.me/dariasigalova)  (preferred contact method)

**Discord:** [dariasi](https://discordapp.com/users/834459180676808704/)

---
## About me
I enjoy getting and improving skills in frontend development. Despite lacking direct experience in this field, I have successfully overcome challenges and achieved goals in other areas. For instance, during my 15 years of work in the tourism industry, I gained experience in project management, team collaboration, and communication with diverse persons. I belive, these skills will be valuable as a frontend developer, where effective collaboration with colleagues is crucial, alongside technical proficiency. 

My interest in programming languages and web development technologies led me to study Python and successfully complete a course at Yandex Practicum. This experience was very interesting for me and now I intend to gain knowledge in another essential field of web development - frontend.


My final goal is to become a reliable and valuable team member, making significant contributions to project development and the attainment of shared objectives.


---

## Skills
* HTML
* CSS (Bootstrap, SCSS)
* Basic knowledge of Python, Django, REST API, SQLite
* Docker
* Git, GitHub
* Figma, Adobe Photoshop

---
## Code example

```python
def get_score(matrix: List[List[str]], k: int) -> int:
    total_num = 2*k
    score = 0
    for i in range(1, 10):
        m = (matrix[0].count(str(i))
             + matrix[1].count(str(i))
             + matrix[2].count(str(i))
             + matrix[3].count(str(i)))
        if m != 0 and m <= total_num:
            score += 1
    return score


def read_input() -> Tuple[List[List[str]], int]:
    k = int(input())
    matrix = []
    for i in range(4):
        matrix.append(list(list(input())))
    return matrix, k


if __name__ == "__main__":
    matrix, k = read_input()
    print(get_score(matrix, k))
```
---
## Experience

* **KMP-Group** travel company (2007-2022)
    - Deputy head of contracting department (2015 - 2022)
    - Manager of contracting department (2011 - 2015)
    - Manager of operating department (2007 - 2011)
    - Receptionist (2007)
* **AGS-Froesch** logistic company (2005-2007)
    - Office manager (2006-2007)
    - Assistant of operating department (2005-2006)

---
## Education

* **Moscow Institute Of Business Administration** (2000-2005)
    + World Economy
* **Yandex Practicum** (2022)
    + Backend Developer (Python)
* **RS School** (2023 - in progress)
    + Frontend Developer

---
## Languages

* **Russian** - native speaker
* **English** - intermediate / upper-intermediate
* **German** - intermediate
* **Turkish** - basic

---

