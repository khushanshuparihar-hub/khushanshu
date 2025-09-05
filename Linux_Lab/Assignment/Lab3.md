# modifying an existing script.
* first we will run a code for print numbers in nano:

1. open enhanced_numbers in nano:

```bash
nano enhanced_numbers.sh
```

2. Add the following code:

```bash
#!/bin/bash

for i in 1 2 3 4 5
do
  echo "Number: $i"
done
```
3. Save and exit:

```bash
(`CTRL+X`, in nano)
```
4. Run it:

```bash
./enhanced_numbers.sh
```
✅ Output should be:

```





