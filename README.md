# c-key-points
<!-- echo "# c-key-points" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SivaPullaiah/c-key-points.git
git push -u origin main -->

# Division and Modulo 
    int/int = int
    
    int/float=float
    float/int=float
    float/float=float

    Modulo operation work only on integers(not float and double types)
    4%2=0
    3%2=1

    but: 5.0%2, 5%2.0 and 5.0%2.0 will not possible
    
    Division with minus:
    ----------------------
    -val/val = val/-val = -result
    val/val = -val/-val = +result
    example:
    -5/2 = -2 and 5/-2 = -2
     5/2 = 2 and -5/-2 = 2

     Modulo with minus:
     --------------------
     -val%val = -val%-val = -result
     *Note:val%val = val%-val = +result