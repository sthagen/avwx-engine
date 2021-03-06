# Other Data Structures

## class avwx.structs.**Aircraft**

#### **from_icao**(*code: str*) -> *avwx.structs.Aircraft*

Load an Aircraft from an ICAO aircraft code

**code**: *str*

**type**: *str*

## class avwx.structs.**Cloud**

**base**: *int* = *None*

**direction**: *str* = *None*

**modifier**: *str* = *None*

**repr**: *str*

**top**: *int* = *None*

**type**: *str* = *str*

## class avwx.structs.**Code**

**repr**: *str*

**value**: *str*

## class avwx.structs.**Fraction**

**denominator**: *int*

**normalized**: *str*

**numerator**: *int*

## class avwx.structs.**Icing**

**ceiling**: *avwx.structs.Number* = *None*

**floor**: *avwx.structs.Number* = *None*

**severity**: *str*

**type**: *str* = *None*

## class avwx.structs.**Location**

**direction**: *avwx.structs.Number*

**distance**: *avwx.structs.Number*

**repr**: *str*

**station**: *str*

## class avwx.structs.**Number**

**repr**: *str*

**spoken**: *str*

**value**: *float*

## class avwx.structs.**RemarksData**

**dewpoint_decimal**: *float* = *None*

**temperature_decimal**: *float* = *None*

## class avwx.structs.**Timestamp**

**dt**: *datetime.datetime*

**repr**: *str*

## class avwx.structs.**Turbulence**

**ceiling**: *avwx.structs.Number* = *None*

**floor**: *avwx.structs.Number* = *None*

**severity**: *str*

## class avwx.structs.**Units**

**altimeter**: *str*

**altitude**: *str*

**temperature**: *str*

**visibility**: *str*

**wind_speed**: *str*
