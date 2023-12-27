A replacement Bootstrap containing a different version of `wget` which works on Remarkable tablets post 3.6.

See http://toltec-dev.org/bootstrap for more information.

To install Toltec, connect your reMarkable to Wi-Fi and paste the following lines in an SSH session:
```bash
wget http://toltec-dev.org/bootstrap
echo "04a28483286f88c5c7f39e352afb62adc57f6162a29fd7e124d832205bb0980e  bootstrap" | sha256sum -c && bash bootstrap
```
