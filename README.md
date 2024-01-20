### Try Except
```
while True:
  try:
    x = int(input('Enter a number: '))
    break
  except:
    print('That\'s not a valid number!')
  print('\nAttempted Input\n')
```
### Try Except Finally
```
while True:
  try:
    x = int(input('Enter a number: '))
    break
  except:
    print('That\'s not a valid number!')
  finally:
    print('\nAttempted Input\n')
```

### Ctrl + C keyboard exit 
```
while True:
  try:
    x = int(input('Enter a number: '))
    break
  except ValueError:
    print('That\'s not a valid number!')
  except KeyboardInterrupt:
    print('\nNo input taken')
  finally:
    print('\nAttempted Input\n')
```

```
try:
    # some code
except ZeroDivisionError as e:
   # some code
   print("ZeroDivisionError occurred: {}".format(e))
```
