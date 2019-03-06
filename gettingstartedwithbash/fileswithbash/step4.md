We can use _cat_ to overwrite the content of the file:

```
cat > hello.txt <<EOL
We
can
write
to multiple
LINES!!!
EOL
```{{execute}}