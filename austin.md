#Lottery-Chart
##<font color=red>分分28/北京28/北京快乐8/福彩3D</font>


###input url
{gameName}	{遊戲名稱}

{count}	{查詢筆數}

####example
/chart?gameName=福彩3D&count=10

-
###output

####<span id= gameType>GameType</span>

>[分分28(77250) | 北京28(77253)](#分分28”)
>
>[北京快乐8(77231)](#北京快乐8)

>[福彩3D(77138)](#福彩3D)

*****
###<font color = green><span id=”分分28”>分分28/北京28</span></font>

>期号
	
	issueCode

>开奖号码

	drawNum

>和值

	totalSumArray

>单双
	
	oddEvenType
	
>大小

	bigSmallType
>边

	side
[return to GameType](#gameType)	
***

###<font color=green><span id=北京快乐8>北京快乐8</span></font>
>期号

	issueCode	

>開獎號碼

	drawNum


>号码分布	

	numDistribution
		"value": "0", 	||	此號碼為0號
       "missing": 1, 	||	此號碼已遺漏1次,若為0則代表此號碼為本次開獎號碼
       "times": null	||	此次開獎此號碼重複出現次數

>大小

	bigSmallType
	
>单双

	oddEvenType
	
>上下

	topBotType
	
>奇偶

	oddEvenCompare
	
>和值

	totalSum
>出现总次数	

	totalAppearanceCount
>平均遗漏值

	averageMissingRate
>最大遗漏值

	maxMissingCount
>最大连出值

	maxConsecutiveWinCount
[return to GameType](#gameType)
***
###<font color=green><span id=福彩3D>福彩3D</span></font>
>期号

	issueCode	
	
>百位

	hundredsPlaceNum
		"value": "0", 	||	此號碼為0號
       "missing": 1, 	||	此號碼已遺漏1次,若為0則代表此號碼為本次開獎號碼
       "times": null	||	此次開獎此號碼重複出現次數
       
>十位

 	tensPlaceNum
 		"value": "2", 	||	此號碼為2號
       "missing": 0, 	||	此號碼已遺漏0次,若為0則代表此號碼為本次開獎號碼
       "times": null	||	此次開獎此號碼重複出現次數

>個位

	onesPlaceNum
		"value": "9", 	||	此號碼為9號
        "missing": 2, 	||	此號碼已遺漏2次,若為0則代表此號碼為本次開獎號碼
       	"times": null	||	此次開獎此號碼重複出現次數
       
>號碼走勢
	
	numDistribution	
		"value": "9", 	||	此號碼為9號
        "missing": 2, 	||	此號碼已遺漏2次,若為0則代表此號碼為本次開獎號碼
     	"times": null	||	此次開獎此號碼重複出現次數
>大小

	bigSmallType
	
>单双

	oddEvenType
	
>質合型態

	primeType
	
>012型態

	zeroOneTwoType
	
>組三

	comboThree
>組六	

	comboSix
>豹子

	sameTripleNum
>跨度

	numRangeValue
>直選和值

	totalSum
>和值尾数

	sumOnesPlaceNum
>百位統計

	hundredsPlaceNumStats{
			出現總次數||totalAppearanceCount
			平均遺漏值||averageMissingRate
			最大遺漏值||maxMissingCount
			最大連出值||maxConsecutiveWinCount
		}
>十位統計

	tensPlaceNumStats{
			出現總次數||totalAppearanceCount
			平均遺漏值||averageMissingRate
			最大遺漏值||maxMissingCount
			最大連出值||maxConsecutiveWinCount
		}
>個位統計

	onesPlaceNumStats{
			出現總次數||totalAppearanceCount
			平均遺漏值||averageMissingRate
			最大遺漏值||maxMissingCount
			最大連出值||maxConsecutiveWinCount
		}
>號碼分佈統計
	
	numDistributionStats{
			出現總次數||totalAppearanceCount
			平均遺漏值||averageMissingRate
			最大遺漏值||maxMissingCount
			最大連出值||maxConsecutiveWinCount
		}


>組三統計

	comboThreeStats{
			出現總次數||totalAppearanceCount
			平均遺漏值||averageMissingRate
			最大遺漏值||maxMissingCount
			最大連出值||maxConsecutiveWinCount
		}

>組六統計

	comboSixStats{
			出現總次數||totalAppearanceCount
			平均遺漏值||averageMissingRate
			最大遺漏值||maxMissingCount
			最大連出值||maxConsecutiveWinCount
		}

>豹子統計

	sameTripleNumStats{
			出現總次數||totalAppearanceCount
			平均遺漏值||averageMissingRate
			最大遺漏值||maxMissingCount
			最大連出值||maxConsecutiveWinCount
		}
[return to GameType](#gameType)
***

##by <font color=pink>Austin</font>