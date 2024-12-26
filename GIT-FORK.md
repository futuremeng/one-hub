<!--
 * @Author: be_loving@163.com 
 * @Date: 2024-12-26 10:59:00
 * @LastEditors: be_loving@163.com 
 * @LastEditTime: 2024-12-26 11:01:16
 * @FilePath: /one-hub/GIT.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# about fork

##  查看是否添加了更新源

    ```
    git remote -v
    ```

## 添加更新源

   ```
   git remote add upstream https://github.com/MartialBE/one-hub.git
   ```

## 添加成功后，查看是否添加成功

## 从源同步更新

   ```
   git fetch upstream
   ```

## 合并源的分支

   ```
   git merge upstream/main
   ```

## 推送到自己的仓库

   ```
   git push
   ```