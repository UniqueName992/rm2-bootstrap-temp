A replacement Bootstrap containing a different version of `wget` which works on Remarkable tablets post 3.6.

See http://toltec-dev.org/bootstrap for more information.

To install Toltec, connect your reMarkable to Wi-Fi and paste the following lines in an SSH session:
```bash
wget http://raw.githubusercontent.com/UniqueName992/rm2-bootstrap-temp/main/bootstrap
echo "91690831e7ead992d357bcc6e233dfaf5a663b57990f6e93c7cd7c38d595e8aa  bootstrap" | sha256sum -c && bash bootstrap
```
