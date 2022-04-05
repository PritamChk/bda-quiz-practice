# BDA Quiz
---
 ## `Requirements`

-  `python` **3.10** or `above`
---
-  Install pipenv using pip in admin mode of cmd or powershell
    > #### `pip install pipenv`
---
-    Clone this Project 
     > git clone link 
     > open it using VS Code

---
- open terminal in VS Code
> For powershell

> - step 1:
```powershell
Set-ExecutionPolicy -Scope CurrentUser Unrestricted
```
> - step 2:
```bash
pipenv sync
```
> - step 3:
```bash
pipenv shell
```
> All setup Done! **Ready to Go!**
---
## How to Use this Quiz
----
> #### For Weekly Practice
> ---

> - Select Week By no

```powershell
bda-quiz startquiz -w -n WEEK_NUMBER
```
> e.g. - bda-quiz startquiz -w -n 3

> - Select week Randomly
```powershell
bda-quiz startquiz
```

> #### For Randomly Practice
> ---
```bash
bda-quiz startquiz -r -q NUM_OF_QUS
```
> - here -r flag is used for select qus randomly
> - -q flag used to specify number of qustions you want to practice
----
### FOR FURTHER HELP WRITE THE FOLLOWING CMD:
```cmd
bda-quiz startquiz --help
```
----
**THANKS**