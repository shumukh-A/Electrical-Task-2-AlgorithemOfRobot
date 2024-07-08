# Electrical-Task-2-AlgorithemOfRobot
# خوارزمية تشغيل محركات من نوع سيرفو موتر لتشكيل حركة مشي الروبوت
للقيام بخطوة أمامية:
# الطرف الأيمن:
<br>يتحرك فخذ الطرف الأيمن إلى الأمام إلى حوالي 50 درجة
<br>تتحرك ركبة الطرف الأيمن إلى الخلف إلى حوالي 30 درجة
<br>تتحرك قدم الطرف الأيمن من 45 درجة إلى 0 درجة
# الطرف الأيسر:
<br>يتحرك فخذ الطرف الأيسر إلى الخلف من 20 إلى 0 درجة
<br>تتحرك ركبة الطرف الأيسر إلى الخلف إلى حوالي 15 درجة
<br>تبقى قدم الطرف الأيسر عند 45 درجة
<br>
<br>بعد ذلك، نقوم بعكس هذه الحركات في كلا الطرفين لإعادتهما إلى الوضع المستقيم الأصلي
<br>لتنفيذ خطوة أمامية أخرى، نكرر الخطوات السابقة ولكن نقوم بتبديل الأدوار بين الطرف الأيمن والطرف الأيسر.

# السودو كود لتنفيذ الخطوة الأمامية للروبوت:
#Initialize joint angles
<br>right_hip = 20
<br>right_knee = 0
<br>right_ankle = 45

<br>left_hip = 20 
<br>left_knee = 0
<br>left_ankle = 45

<br>#Perform step
<br>#Right Leg
<br>right_hip = 50
<br>right_knee = 30
<br>right_ankle = 0

<br>#Left Leg 
<br>left_hip = 0
<br>left_knee = 15
<br>left_ankle = 45

<br>#Return to start position
<br>#Right Leg
<br>right_hip = 20
<br>right_knee = 0 
<br>right_ankle = 45

<br>#Left Leg
<br>left_hip = 20
<br>left_knee = 0
<br>left_ankle = 45

<br>#Repeat for next step
<br>#Swap right and left leg movements
