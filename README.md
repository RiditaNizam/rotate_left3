# rotate_left3
CodingBat Python List-1

Given an array of ints length 3, return an array with the elements "rotated left" so {1, 2, 3} yields {2, 3, 1}.

def rotate_left3(nums):

    answerList = []
  
    answerList.append(nums[1])
  
    answerList.append(nums[2])
  
    answerList.append(nums[0])
  
    return answerList
