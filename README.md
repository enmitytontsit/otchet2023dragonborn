#python

max_num = -1000000
nums = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
for num in nums:
    if num > max_num:
	max_num = num
print(max_num)   	#Ответ:10

#Описание: Вводим n - целое число с клавиаутуры, вводим n целых чисел с клавиатуры и закидывает их в списочное выражение. Проходимся по каждому элементу списка и проверяем его, больше он нашего максимального значения или нет. Если больше то он меняет максимальное значение на наше число, если не больше то ничего не меняет