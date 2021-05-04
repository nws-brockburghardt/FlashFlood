# FlashFlood

###Verification
#run the following code to append all RRX (FFW ML model) files to a master file.
touch masterRRX.txt

for dir in /var/www/html/archive/2020/*/; do 
	cat "${dir}RRXSLC" >> masterRRX.txt ; 
done
