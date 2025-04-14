## Git 指令練習

### 基本指令介紹

1. **git init**  
   初始化一個新的 Git 儲存庫。執行此指令後，會在目錄中建立一個 `.git` 資料夾。  
   ```bash
   git init
   ```

2. **git clone**  
   從遠端儲存庫複製一個專案到本地端。  
   ```bash
   git clone <repository-url>
   ```

3. **git status**  
   查看目前儲存庫的狀態，例如檔案是否有變更、是否已加入暫存區等。  
   ```bash
   git status
   ```

4. **git add**  
   將檔案加入到暫存區，準備提交。  
   ```bash
   git add <file>
   ```
   或加入所有變更：  
   ```bash
   git add .
   ```

5. **git commit**  
   提交暫存區的變更，並加入提交訊息。  
   ```bash
   git commit -m "提交訊息"
   ```

6. **git push**  
   將本地端的提交推送到遠端儲存庫。  
   ```bash
   git push origin <branch-name>
   ```

7. **git pull**  
   從遠端儲存庫拉取最新的變更並合併到本地分支。  
   ```bash
   git pull
   ```

8. **git branch**  
   查看、建立或刪除分支。  
   查看目前分支：  
   ```bash
   git branch
   ```
   建立新分支：  
   ```bash
   git branch <branch-name>
   ```
   刪除分支：  
   ```bash
   git branch -d <branch-name>
   ```

9. **git checkout**  
   切換到指定分支或提交版本。  
   ```bash
   git checkout <branch-name>
   ```

10. **git merge**  
    合併分支到目前所在的分支。  
    ```bash
    git merge <branch-name>
    ```

11. **git log**  
    查看提交歷史記錄。  
    ```bash
    git log
    ```

12. **git remote**  
    管理遠端儲存庫。  
    查看遠端儲存庫：  
    ```bash
    git remote -v
    ```
    新增遠端儲存庫：  
    ```bash
    git remote add origin <repository-url>
    ```

13. **git reset**  
    重置暫存區或提交。  
    ```bash
    git reset <file>
    ```
    或重置到指定提交：  
    ```bash
    git reset --hard <commit-hash>
    ```

14. **git stash**  
    暫存目前的變更，並清空工作目錄。  
    ```bash
    git stash
    ```
    恢復暫存的變更：  
    ```bash
    git stash pop
    ```

15. **git diff**  
    比較檔案的差異。  
    ```bash
    git diff
    ```

以上是 Git 的基本指令介紹，適合初學者快速上手。