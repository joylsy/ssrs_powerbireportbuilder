Chart Series Labels

=Iif(val(Fields!VALUE.Value)>.081,"#VALY{##0.0%}","#LEGENDTEXT" & SPACE(2) & "#VALY{##0.0%}") &
iif(val(Fields!VALUE.Value)<=.081,iif(trim(Fields!TYPENAME_DESC.Value) = "IOC", 
" " & vbcrlf  & vbcrlf ," " & vbcrlf  & vbcrlf  & vbcrlf   & vbcrlf ),"")



![Alt text](https://github.com/joylsy/ssrs_powerbireportbuilder/blob/main/chart_label_positioning.png "Optional title")
