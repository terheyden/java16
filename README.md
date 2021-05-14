# Java 16 template

Includes, what I consider, must-have dependencies and settings.

## How to use

1. Clone this bad boy
2. Delete the .git folder
3. Search-and-replace your group and artifact names:
```
gsed -i -Ee 's/com\.terheyden/com.GROUP/g' $(find . -type f)
gsed -i -Ee 's/java16/ARTIFACT/g' $(find . -type f)
```
