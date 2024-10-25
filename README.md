# Useful RegEX Patterns 


<picture>
  <img alt="Webpage Time" src="https://i0.wp.com/digitalfortress.tech/wp-content/uploads/2018/05/regex_horiz.jpg" width="300" height="100">
</picture>


## Useful Notepad++ regex patterns

1. Find and Replace Windows Special characters

    \r\n --> \n

2. Select text after fixed position

    .{11}\K.+$ (Select all characters after 11th position)

3. Select fixed characters from text begining

    ^.{0,10} (Select first 10 characters)

4. Select hour part from timestamp (Ex: yyyy-mm-dd hh:mm:ss --> hh:mm:ss)

   \s\d{2}:\d{2}:\d{2}
