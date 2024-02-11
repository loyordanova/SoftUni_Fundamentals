text1 = input().split(', ')
text2 = input().split(', ')

final_list = []

for word2 in text1:
    for word1 in text2:
        if word2 in word1:
            final_list.append(word2)

res = []
[res.append(x) for x in final_list if x not in res]
print(res)
