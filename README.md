INPUT "Enter A Number" ; N 
If N < 10 AND 0 < N THEN 
  PRINT N ; "Is A Single Digit Positive Number." 
ELESEIF N >= 10 AND N <= 99 THEN 
  PRINT N ; "Is A Double Digit Positive Number." 
ELSEIF N >= 100 AND N >= 999 THEN 
  PRINT N ; "Is A Triple Digit Positive Number." 
ELSE 
  PRINT N ; "Is Not In Any Of The Given Range" 
END IF 
