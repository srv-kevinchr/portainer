Execute:
```
sudo bash -c 'cat > /etc/docker/daemon.json << EOF
{
"min-api-version": "1.41"
}
EOF
' && sudo systemctl restart docker
```
