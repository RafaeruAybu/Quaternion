# Quaternion (Ongoing)
Operations with quaternions. C++ project.

Yep... i^2 = j^2 = k^2 = ijk = -1.

<pre>
Q1 = a + bi + cj + dk
Q2 = e + fi + gj + hk
</pre>

<pre>
Q1*Q2 = ae  + afi   + agj   + ahk
        bei + bfi^2 + bgij  + bhik
        cej + cfji  + cgj^2 + chjk
        dek + dfki  + dgkj  + dhk^2
</pre>

|             |      i           | j            |  k            |
| :---        |    :----:        |   :----:     |          ---: |
| i           | -1               | k            | -j            |
| j           | -k               | -1           | i             |
| k           | j                | -i           | -1            |

<pre>
Q1*Q2 = (ae - bf - cg - dh,
         af + be + ch - dg,
         ag - bh + ce + df,
         ah + bg - cf + de)
</pre>
