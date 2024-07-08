# Electrical-Task-2-AlgorithemOfRobot
للقيام بخطوة أمامية:
# الطرف الأيمن:
يتحرك فخذ الطرف الأيمن إلى الأمام إلى حوالي 50 درجة
تتحرك ركبة الطرف الأيمن إلى الخلف إلى حوالي 30 درجة
تتحرك قدم الطرف الأيمن من 45 درجة إلى 0 درجة
# الطرف الأيسر:
يتحرك فخذ الطرف الأيسر إلى الخلف من 20 إلى 0 درجة
تتحرك ركبة الطرف الأيسر إلى الخلف إلى حوالي 15 درجة
تبقى قدم الطرف الأيسر عند 45 درجة
بعد ذلك، نقوم بعكس هذه الحركات في كلا الطرفين لإعادتهما إلى الوضع المستقيم الأصلي
لتنفيذ خطوة أمامية أخرى، نكرر الخطوات السابقة ولكن نقوم بتبديل الأدوار بين الطرف الأيمن والطرف الأيسر.

# السودو كود لتنفيذ الخطوة الأمامية للروبوت:
#Initialize joint angles
right_hip = 20
right_knee = 0
right_ankle = 45

left_hip = 20 
left_knee = 0
left_ankle = 45

#Perform step
#Right Leg
right_hip = 50
right_knee = 30
right_ankle = 0

#Left Leg 
left_hip = 0
left_knee = 15
left_ankle = 45

#Return to start position
#Right Leg
right_hip = 20
right_knee = 0 
right_ankle = 45

#Left Leg
left_hip = 20
left_knee = 0
left_ankle = 45

#Repeat for next step
#Swap right and left leg movements
