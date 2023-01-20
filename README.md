# pythonodev1
python ödev 1
l = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
flatten_list = []
def flatten (b):
    for sublist in b:
        if type(sublist) == list
            flatten(sublist)
        else:
            flatten_list.append(sublist)
        return flatten_list
    print(flatten(l))
    
  #  pythonodev2
  
  l = [[1, 2], [3, 4], [5, 6, 7]]
flatten_list = []
def flatten (b):
    for sublist in b:
        if type(sublist) == list
            flatten(sublist[-1])
        else:
            flatten_list.append(sublist[-1])
        return flatten_list
    print(flatten(l[-1]))
