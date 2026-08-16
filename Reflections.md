7. *resets the box sizing.
a. with the width being 200px the browser will shrink the content area to mak eroom for the padding so that the box stays exactly 200px. Hence the content area will be (200-40)= 160px.
b.  without thr border box, the default is content box and to identify the rended width its equivalent to = width + paddinng-left + padding-right + border-left + border-right
= 200px + 20px +20px + 0
=240px

8. The badge jumps out of the card entirely and positions itself relative to the whole page making it land at the top-right corner of the browser window and not of the card. This is because absolute under position always needs something to be positioned relative to.
9. Green :  h2{color:red} specifity: 001
.title {color:blue} specificity: 010
h2.title{color:green} specificity: 011

10. static: default and ordinary floe. AN example is the wikipedia article they just top to bottom in normal redaing order.
relative:icon badges an dexample i sthe whatsapp web with a small unread meassage count buble sitting slightly from its default position
absolute: an element poured out of the flow and positioned inside a specific container. an exmaple is the label; sponsored on instagram ad post.. it is pinned to a fixed spot inside the post card regardless of how much text is above the post.
fixed: stays glues to the viewport even when scorrling. An example is the floating whatsapp chat button that many websites have in the bottom right corner or the in message chatbot.
sticky:behaves normally until a threshold is reached. For exaple the gmail search bar at the top of the viewport an dsticks when scolling the content below
