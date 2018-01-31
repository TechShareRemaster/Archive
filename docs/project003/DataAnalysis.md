# 데이터 분석 기초 with 파이썬

- 참여자: 조규진

## 계획

- 목표: 4차에 진행할 **Data Visualization 프로젝트를 위한 밑밥** 깔기
- 방법: Udacity 강좌 수강


1. [Introduction to Python](https://www.udacity.com/course/introduction-to-python--ud1110): 3주
2. [Intro to Data Analysis](https://www.udacity.com/course/intro-to-data-analysis--ud170): 5주
3. [Introduction to Statistics](https://www.udacity.com/course/intro-to-statistics--st101): 2주
4. [Creating an Analytical Dataset](https://www.udacity.com/course/creating-an-analytical-dataset--ud977): 2주


## 1주

- [Introduction to Python](https://www.udacity.com/course/introduction-to-python--ud1110)
  - [x] **Lesson 1. Numbers and Strings**
    - `**`: js에도 있었음.. 충격.., `//`
    - `aeb` 형태의 scientific notation
    - `string*number = stringstringstring... n번`
    - `title(), isLower(), count()` 등 string methods
    - `string_template.format()`
  - [x] **Lesson 2. Functions, Installation and Conditionals**
  - [ ] Lesson 3. Data Structures and Loops
  - [ ] Lesson 4. Files and Modules
  - [ ] Lesson 5. Wikipedia Web Crawl Case Study

## 2주
- [Introduction to Python](https://www.udacity.com/course/introduction-to-python--ud1110)
  - [x] Lesson 1. Numbers and Strings
  - [x] Lesson 2. Functions, Installation and Conditionals
  - [x] **Lesson 3. Data Structures and Loops**
    - TypeScript에서 처음 본 Tuple을 만남
    - JS에 비해 자료형이 더 다양하다고 느낌(ES6에 Set, Map이 있지만 실제로 얼마나 사용할지?)
  - [ ] Lesson 4. Files and Modules
  - [ ] Lesson 5. Wikipedia Web Crawl Case Study

  ## 3주
- [Introduction to Python](https://www.udacity.com/course/introduction-to-python--ud1110)
  - [x] Lesson 1. Numbers and Strings
  - [x] Lesson 2. Functions, Installation and Conditionals
  - [x] Lesson 3. Data Structures and Loops
  - [x]ㅈ **Lesson 4. Files and Modules**
    - Default variables
      ```python
        def todo_list(new_task, base_list=['wake up']):
          base_list.append(new_task)
          return base_list

        todo_list("check the mail")
        todo_list("begin orbital transfer")
        """ >>> ['wake up', 'check the mail', 'begin orbital transfer'] ???? """
      ```
    - `UnboundLocalError`: Python doesn't allow functions to modify variables that aren't in the function's scope.

  - [...] **Lesson 5. Wikipedia Web Crawl Case Study**