A replacement Bootstrap containing a different version of `wget` which works on Remarkable tablets post 3.6.

See http://toltec-dev.org/bootstrap for more information.

To install Toltec, connect your reMarkable to Wi-Fi and paste the following lines in an SSH session:
```bash
wget http://raw.githubusercontent.com/UniqueName992/rm2-bootstrap-temp/main/bootstrap
echo "86fc5df07d57673fe8398a204446cccb60feee451c58ecc1381d0aa590ffc4c2  bootstrap" | sha256sum -c && bash bootstrap
```
