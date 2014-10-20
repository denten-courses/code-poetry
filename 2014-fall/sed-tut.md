### Findly
```
find . -name "*.md"
grep ly
wc
grep ly | wc
sort test.md | uniq -c
```

### Turning day into night
```
sed 's/day/night/' 24hr.txt
echo day | sed s/day/night/
sed -i .bak 's/day/night/' 24.txt
sed 's/day/night/' 24hr.txt
```
### Putting all your eggs in one basket
```
find . -type f -name "*.md" | xargs grep "orange" | sed s/orange/apple/ >> apple.txt
```

### Rewriting Moby Dick
```
cat pg2701.txt | sed 's/\s/\n/g' | sort | uniq -c | sort -hr > test.txt
find . -name "test*" | xargs sed -i 's/apple/orange/g'
or find . -name "test*" -exec sed -i 's/apple/orange/g'
```
