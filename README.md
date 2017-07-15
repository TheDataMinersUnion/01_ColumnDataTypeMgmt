# 01_ColumnDataTypeMgmt
Sample files used in ColumnDataTypeMgmt

Below is a copy of the M code used to generate the DataType lookup table used in the file.

# M Snip:
#table(<br>
    {"DataTypeName","DataType"},<br>
    {<br>
        {"WholeNum", Int64.Type},<br>
        {"DecNum", type number},<br>
        {"Percent", Percentage.Type},<br>
        {"Currency", Currency.Type},<br>
        {"Date", type date},<br>
        {"Time", type time},<br>
        {"DateTime", type datetime},<br>
        {"Text", type text},<br>
        {"T/F", type logical}<br>
    }<br>
)<br>

