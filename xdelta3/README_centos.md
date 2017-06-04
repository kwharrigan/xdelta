# Readme for CentOS

## Known package dependencies

gcc-c++  
libtool  
autoconf  
automake  

## To compile

```
libtoolize --force
aclocal
autoheader
automake --force-missing --add-missing
autoconf
./configure
make
```

