Link : https://www.hackerrank.com/challenges/py-set-discard-remove-pop/problem

@Abhrajyoti Kundu

n = int(input())
s = set(map(int, input().split()))
N = int(input())
for i in range(N):
    text= input()
    if text == 'pop':
        s.pop()
    elif text[0] == 'd':
        s.discard(int(text.split()[1]))
    elif text[0] == 'r':
        s.remove(int(text.split()[1]))

print(sum(list(s)))
