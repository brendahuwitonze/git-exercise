
## Advanced git  excercise solution

### part 1  Refining Git History
```bash
1509  touch test{1..4}.md
 1510  git add test1.md && git commit -m "chore: Create initial file"
 1511  git add test2.md && git commit -m "chore: Create another file"
 1512  git add test3.md && git commit -m "chore: Create third and fourth files"
 1513  git status 
 1514  -rf    README.md
 1515  git log
 1516  git add test4.md
 1517  git commit --amend -m "Updated commit message with test4.md"
 1518  git rebase -i HEAD~2
 1519  clear
 1520  git log
 1521  git rebase -i HEAD~2
 1522  git log
 1523  git rebase -i HEAD~1
 1524  git log
 1525  git rebase -i HEAD~3
 1526  git rebase -i HEAD~2
 1527  git rebase --continue | --abort | --skip
 1528  git init
 1529  touch test{1..4}.md
 1530  git add test1.md && git commit -m "chore: Create initial file"
 1531  git add test2.md && git commit -m "chore: Create another file"
 1532  git add test3.md && git commit -m "chore: Create third and fourth files"
 1533  git add test4.md
 1534  git rebase -i HEAD~2
 1535  git status
 1536  git push origin master
 1537  git push origin main
 1538  git status
 1539  git push origin main
 1540  git rebase -i HEAD~2
 1541  git commit -- amend -m "updated commit message with "updated the commit message with test.md4"
git commit -- amend -m "updated commit message with "updated the commit message with test.md4"
 1542  git commit --amend -m "Updated commit message with test4.md"
 1543  git rebase -i HEAD~2
 1544  git rebase --continue
 1545  git rebase --edit-todo
 1546  git log
 1547  git rebase --edit-todo
 1548  git log
 1549  git rebase --edit-todo
 1550  git log
 1551  git rebase --edit-todo
 1552  git log
 1553  git status
 1554  git rebase --continue
 1555  git log
 1556  git rebase --continue
 1557  git rebase -i HEAD~2
 1558  git log
 1559  git reset
 1560  git log
 1561  git reset HEAD~
 1562  git log
 1563  git status
 1564  git commit -m "Create third file" and "Create fourth file"
 1565  git log
 1566  git reset 73d775248280c4f6ecd554787f55a3d582ea8716
 1567  git log
 1568  git rebase -i HEAD~2
 1569  git log
 1570  git rebase --continue
 1571  git push origin main
 1572  git pull
 1573  git pull rebase true
 1574  clear
 1575  git pull
1600  git branch ft/branch, 
 1601 git log ft/branch, --oneline
 1622  git checkout main
 1623  git cherry-pick 5f922cf 
 1626  git log --graph
 ```

 

 ### part2 
 ```bash
 1722  git branch -d ft/new-feature
 1723  git checkout -b ft/new-branch-from-commit commit-hash
 1724  git checkout -b ft/new-branch-from-commit 
 1725  git branch -d ft/new-branch-from-commit 
 1726  git checkout main
 1727  git branch -d ft/new-branch-from-commit
 1728  git log
 1729  git add.
 1730  git commit -m "Your commit message"
 1731  git log --oneline
 1732  git checkout -b ft/new-branch-from-commit 051265e
 1733  git status
 1734  git push origin ft/new-branch-from-commit
 1735  git checkout main
 1736  git merge -m "merged the ft/new-branch-from-commit ,into main" ft/new-branch-from-commit
 1737  git push origin master
 1738  git push origin main
  1763  git checkout ft/new-branch-from-commit
 1764  git rebase main
 1765  git status
 1766  git log
  1768  git branch -m ft/new-branch-from-commit ft/improved-branch-name
 1769  git log --oneline
 1770  git checkout 4f4305cgit
```


### part 3

```bash

1782  git stash
 1783  git status
 1784  git stash
 1785  git stash pop
 1786  git branch
 1787  git add .
 1788  git commit -m "added file in main"
 1789  git checkout   ft/improved-branch-name
 1790  git add .
 1791  git commit -m "changed the line"
 1792  git rebase main
 1793  git status
 1794  git add .
 1795  git status
 1796  git checkout main
 1797  git status
 1798  git push origin main
  1811  git mergetool --tool-help
 1812  git commit -m "Resolved merge conflicts"



