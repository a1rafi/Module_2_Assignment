# Assignment - Module 2

## Al Rafi Ahmed

### Git Commands

#### Task 1

```bash
git init
```

```bash
git add .
```

```bash
git branch -M Main
```

```bash
git commit -m "First commit"
```

```bash
git checkout -b develop
```

```bash
git checkout -b feature/login
```
![Task 1](/media/alrafi/6EDA7E86DA7E4A7B/DevOps/Assignments/Module2/ss/Task1 M2.png)

#### Task 2

```bash
git checkout develop
git checkout -b feature/payment
```

```bash
git checkout develop
git checkout -b feature/profile
```

```bash
git checkout develop
git checkout -b bugfix/login-error
```

```bash
git checkout feature/payment
git add .
git commit -m "feat:payment txt added"

git switch feature/profile
git add .
git commit -m "feat:profile txt added"
```

```bash
git switch develop
git add .
git commit -m "develop branch first commit"
git merge feature/payment
```

```bash
git checkout feature/profile
git rebase develop
```

```bash
git checkout develop
git merge feature/profile
```

![Task 2](/media/alrafi/6EDA7E86DA7E4A7B/DevOps/Assignments/Module2/ss/Task2 M2.png)

![Task 2.1](/media/alrafi/6EDA7E86DA7E4A7B/DevOps/Assignments/Module2/ss/Task2.1 M2.png)


#### Task 3

```bash
git add .
git commit -m "payment branch first commit"

git add .
git commit -m "payment branch second commit"

git add .
git commit -m "payment branch third commit"

git add .
git commit -m "payment branch fourth commit"

git add .
git commit -m "payment branch fifth commit"
```

```bash
git rebase -i HEAD~5
```

![Task 3](/media/alrafi/6EDA7E86DA7E4A7B/DevOps/Assignments/Module2/ss/Task3 M2.png)


```bash
git remote add origin https://github.com/a1rafi/Module_2_Assignment.git
git push -u origin main
git push origin --all
```