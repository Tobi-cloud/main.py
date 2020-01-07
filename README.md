# main.py
python practice
my_list=[1,2,3,4,5,6,7,8.9,9,10]

#add in list


def sumLists(someLists):
        sums=0
        length=len(someLists)-1
        for i in range(length):
            ans=someLists[i] + someLists[i+1]
            sums=sums+ans
        print(sums) 

sumLists(my_list)