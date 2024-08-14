# Git TAG
- mark the point of the code specific commit.. i.e. when we release or add major feature
  
  
https://www.youtube.com/watch?v=spkUevg1NqM&list=PLe6EXFvnTV7-_41SpakZoTIYCgX4aMTdU

```bash
# lightweight tag, only name the point
git tag <tagName>

# tag with a message attached
git tag -a <tagName> -m "message"

# list of all the tags and messages
git tag -n

# delte the tag
git tag --delete (-d) <tagName> 
```