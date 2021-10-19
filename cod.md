import cv2

CALLOFDUTY = {'BO4': 1,'COD':2,'COLD WAR':3,'MW1':4,'MW2':5,'MW3':6,'MW2019':7,'VANGUARD':8,'WARZONE':9,'WWII':10}

text = input('введите название колды:')


if CALLOFDUTY[text] == 1:
    img = cv2.imread('BO4.jpg')
    cv2.imshow('допустим ква', img)
    cv2.waitKey(10000)

elif CALLOFDUTY[text] == 2:
    img = cv2.imread('COD.jpg')
    cv2.imshow('допустим ква', img)
    cv2.waitKey(10000)

elif CALLOFDUTY[text] == 3:
    img = cv2.imread('COLD WAR.jpg')
    cv2.imshow('допустим ква', img)
    cv2.waitKey(10000)

elif CALLOFDUTY[text] == 4:
    img = cv2.imread('MW1.jpg')
    cv2.imshow('допустим ква', img)
    cv2.waitKey(10000)

elif CALLOFDUTY[text] == 5:
    img = cv2.imread('MW2.jpg')
    cv2.imshow('допустим ква', img)
    cv2.waitKey(10000)

elif CALLOFDUTY[text] == 6:
    img = cv2.imread('MW3.jpg')
    cv2.imshow('допустим ква', img)
    cv2.waitKey(10000)

elif CALLOFDUTY[text] == 7:
    img = cv2.imread('MW2019.jpg')
    cv2.imshow('допустим ква', img)
    cv2.waitKey(10000)

elif CALLOFDUTY[text] == 8:
    img = cv2.imread('VANGUARD.jpg')
    cv2.imshow('допустим ква', img)
    cv2.waitKey(10000)

elif CALLOFDUTY[text] == 9:
    img = cv2.imread('WARZONE.jpg')
    cv2.imshow('допустим ква', img)
    cv2.waitKey(10000)

elif CALLOFDUTY[text] == 10:
    img = cv2.imread('WWII.jpg')
    cv2.imshow('допустим ква', img)
    cv2.waitKey(10000)





