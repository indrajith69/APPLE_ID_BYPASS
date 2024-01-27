# Activation Lock Bypass

This is a tool for bypassing the activation lock using a silver server on certain apple devices (tested for ipad2)

## Usage

1) Create a php server on cloud or locally using tools like xAMPP and host the silver.php file on it
2) Open powershell on the extracted zip's directory and execute the following command (replace content inside "<" and ">" with the server address)

```bash
ideviceactivation activate -s <http://127.0.0.1:5000/> -d
```
[video demonstration](https://user-images.githubusercontent.com/66301495/121471931-19efca00-c9de-11eb-97b4-b6bf217c89c7.mp4)
