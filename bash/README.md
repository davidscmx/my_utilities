Usage of utilities

# Rename files by adding padding zeros.
- Default 6 zeros
- ```for i in *.png;do mv $i `./zeropad.sh $i`; done```