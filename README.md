# Lowest
 Else                 $iHighest = $vInput[$i]             EndIf         EndIf          If StringLen(String(10^$vInput[$i])) > StringLen(String(10^$iLowest)) Then             If StringLeft(String(10^$vInput[$i]), 1) = "0" Then ; Negative Number                 $iLowest = $vInput[$i]             Else                 ;;;             EndIf         EndIf      Next      Return $iLowest &amp; ", " &amp; $iHighest  EndFunc  
