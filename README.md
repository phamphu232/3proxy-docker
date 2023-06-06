# Squid Docker

## Add user

  ```
  docker exec 3proxy sh -c "/add3proxyuser.sh YOUR_USERNAEM YOUR_PASSWORD"
  ```

## Testing

  ```
  curl -v -x socks5://YOUR_USERNAEM:YOUR_PASSWORD@localhost:1081 http://www.google.com/
  ```

## Referent

 - https://github.com/3proxy/3proxy
