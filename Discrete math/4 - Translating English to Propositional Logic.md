# Translating Eng $\to$ Logic
1. Identify atomic propositions
2. Determine appropriate logical connections (connectives)

## Examples
If I go to the store or the movies, I won't do my homework.
p: I go to the store.
q: I go to the movies.
r: I do my homework

Result: $(p\vee q)\to \neg r$

## Practices
1. You can get a free sandwich on Thursday if you buy a sandwich or a cup of soup.
2. You can get a free sandwich on Thursday only if you buy a sandwich or a cup of soup.
3. The automated reply can't be sent when the system is full.

# Translating Logic $\to$ Eng
q: You can ride the roller coaster.
r: you are under 4 feet tall.
s: you are older than 16 years old.

Translate: $(r\vee \neg s)\to \neg q$

If you are under 4 feet tall or you aren't older than 16 then you can't ride the roller coaster.

The order of operation is as following:

| Operator | Precedence |
| ---- | ---- |
| $\neg$ | 1 |
| $\vee$  | 2 |
| $\wedge$  | 3 |
| $\to$ | 4 |
| ↔ | 5 |


# Using bitwise with 0 and 1s

(11011 $\oplus$ 00101) $\lor$ (11101 $\land$ 01111)

The first part:
11110

The second part:
01101

Combined:
11111