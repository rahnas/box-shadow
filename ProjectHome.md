CSS for box-shadow is:
box-shadow: 10px 10px 5px #888; padding: 5px 5px 5px 15px;

For older version of Firefox, you might have to add -moz- and for Safari and Chrome, try -webkit- as prefix. (My Chrome is already supporting without any prefix).

So, here what you need for IE to make box-shadow.

behavior: url(box-shadow.htc);