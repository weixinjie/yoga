---
path: "/docs/align-content"
title: "Align Content"
hasPlayground: true
initialPlayground: eyJ3aWR0aCI6NTAwLCJoZWlnaHQiOjUwMCwiYWxpZ25Db250ZW50IjoxLCJmbGV4V3JhcCI6MSwiY2hpbGRyZW4iOlt7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJtaW5XaWR0aCI6bnVsbCwibWF4V2lkdGgiOm51bGwsIm1pbkhlaWdodCI6bnVsbCwibWF4SGVpZ2h0IjpudWxsfSx7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJtaW5XaWR0aCI6bnVsbCwibWF4V2lkdGgiOm51bGwsIm1pbkhlaWdodCI6bnVsbCwibWF4SGVpZ2h0IjpudWxsfSx7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJtaW5XaWR0aCI6bnVsbCwibWF4V2lkdGgiOm51bGwsIm1pbkhlaWdodCI6bnVsbCwibWF4SGVpZ2h0IjpudWxsfSx7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJtaW5XaWR0aCI6bnVsbCwibWF4V2lkdGgiOm51bGwsIm1pbkhlaWdodCI6bnVsbCwibWF4SGVpZ2h0IjpudWxsfSx7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJtaW5XaWR0aCI6bnVsbCwibWF4V2lkdGgiOm51bGwsIm1pbkhlaWdodCI6bnVsbCwibWF4SGVpZ2h0IjpudWxsfSx7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJtaW5XaWR0aCI6bnVsbCwibWF4V2lkdGgiOm51bGwsIm1pbkhlaWdodCI6bnVsbCwibWF4SGVpZ2h0IjpudWxsfSx7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJtaW5XaWR0aCI6bnVsbCwibWF4V2lkdGgiOm51bGwsIm1pbkhlaWdodCI6bnVsbCwibWF4SGVpZ2h0IjpudWxsfSx7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJtaW5XaWR0aCI6bnVsbCwibWF4V2lkdGgiOm51bGwsIm1pbkhlaWdodCI6bnVsbCwibWF4SGVpZ2h0IjpudWxsfSx7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJtaW5XaWR0aCI6bnVsbCwibWF4V2lkdGgiOm51bGwsIm1pbkhlaWdodCI6bnVsbCwibWF4SGVpZ2h0IjpudWxsfSx7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJhbGlnbkNvbnRlbnQiOjIsIm1pbldpZHRoIjpudWxsLCJtYXhXaWR0aCI6bnVsbCwibWluSGVpZ2h0IjpudWxsLCJtYXhIZWlnaHQiOm51bGx9XSwibWluV2lkdGgiOm51bGwsIm1heFdpZHRoIjpudWxsLCJtaW5IZWlnaHQiOm51bGwsIm1heEhlaWdodCI6bnVsbH0=
---

## Align Content

Align content defines the distribution of lines along the cross-axis. This only
has effect when items are wrapped to multiple lines using [`flex wrap`](/docs/flex-wrap).

**FLEX START (DEFAULT)** Align wrapped lines to the start of the container's cross axis.

**FLEX END** Align wrapped lines to the end of the container's cross axis.

**STRETCH** Stretch wrapped lines to match the `height` of the container's cross axis.

**CENTER** Align wrapped lines in the center of the container's cross axis.

**SPACE BETWEEN** Evenly space wrapped lines across the container's main axis, distributing
remaining space between the lines.

**SPACE AROUND** Evenly space wrapped lines across the container's main axis, distributing
remaining space around the lines. Compared to `space between` using
`space around` will result in space being distributed to the begining of
the first lines and end of the last line.

<controls prop="alignContent"></controls>
