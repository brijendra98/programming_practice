# No Prefix Set

Given *N* strings. Each string contains only lowercase letters from *a-j*(both inclusive). The set of *N* strings is said to be **GOOD SET** if no string is **prefix** of another string else, it is **BAD SET**.(If two strings are identical, they are considered prefixes of each other.)

For example, *aab*, *abcde*, *aabcd* is BAD SET because *aab* is prefix of *aabcd*.

Print **GOOD SET** if it satisfies the problem requirement.
Else, print **BAD SET** and the first string for which the condition fails.

## Input Format

First line contains *N*, the number of strings in the set.
Then next *N* lines follow, where *ith* line contains *ith* string.

## Constraints

1 <= *N* <= 10^5
1 <= Length of the string <= 60

## Output Format

Output `GOOD SET` if the set is valid.
Else, output `BAD SET` followed by the first string for which the condition fails.

## Sample Input00

```
7
aab
defgab
abcde
aabcde
cedaaa
bbbbbbbbbb
jabjjjad
```

## Sample Output00

```
BAD SET
aabcde
```

## Sample Input01

```
4
aab
aac
aacghgh
aabghgh
```

## Sample Output01

```
BAD SET
aacghgh
```
