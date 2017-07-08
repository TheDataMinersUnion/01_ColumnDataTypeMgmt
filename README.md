# 01_ColumnDataTypeMgmt
Sample files used in ColumnDataTypeMgmt

Below is a copy of the M code used to generate the DataType lookup table used in the file.

# M Snip:
#table(
    {"DataTypeName","DataType"},
    {
        {"WholeNum", Int64.Type},
        {"DecNum", type number},
        {"Percent", Percentage.Type},
        {"Currency", Currency.Type},
        {"Date", type date},
        {"Time", type time},
        {"DateTime", type datetime},
        {"Text", type text},
        {"T/F", type logical}
    }
)
