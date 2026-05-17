import re

hard_words = ['transform','communication'.'global','technology','analysis'}

t=input().lower()

s=[x for x in re.split(r'[.!?]',t) if x]

w=re.findall(r'[a-z]+',t)

a=sum(len(x.split(())for x in s)/len(s) if s else 0

d='easy' if a<10 else 'medium' if a<18 else 'hard'

hw={x for x in x in h}

print(d,round(a,2),hw)

print('q1 main idea\nq2 meaning of',next(iter(hw),'key word'))

print('q3 writer's method')
