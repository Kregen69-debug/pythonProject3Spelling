from textblob import TextBlob
myt= ["incordfrect","spellingfh"]

corrected_list = []
for word in myt:
    corrected_list.append(TextBlob(word))
print("Corrected list are:")
for word in corrected_list:
    print(word.correct(), end = " ")
