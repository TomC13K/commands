# Git TAG
- mark the point of the code specific commit.. i.e. when we release or add major feature
  
  
https://www.youtube.com/watch?v=spkUevg1NqM&list=PLe6EXFvnTV7-_41SpakZoTIYCgX4aMTdU

```bash
# lightweight tag, only name the point
git tag <tagName>
git tag v1.4-lw

# tag with a message attached
git tag -a <tagName> -m "message"
git tag -a v1.4 -m "my version 1.4"

# show list of all tags
git tag
git tag -n    # list of all the tags with messages

# delte the tag
git tag --delete (-d) <tagName> 

```