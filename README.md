A replacement Bootstrap containing a different version of `wget` which works on Remarkable tablets post 3.6.

See https://toltec-dev.org/#install-toltec for more information.

To install Toltec, connect your reMarkable to Wi-Fi and paste the following lines in an SSH session:
```bash
wget http://raw.githubusercontent.com/UniqueName992/rm2-bootstrap-temp/main/bootstrap
echo "a94ddad2aae1b560f5ff168dc309d4c4e39a4723136010253c31cdf3c5c5faad  bootstrap" | sha256sum -c && bash bootstrap
```
