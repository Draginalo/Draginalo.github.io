body {
  background-color: blue;
}
/* header*/
.bpw-header-container {
  background: url(images/header.png) no-repeat;
  background-size: 100% 100%;
}
.bpw-bot-avatar img,
.bpw-bot-avatar svg {
  background: none;
}
/* bot chat bubble*/
.bpw-chat-bubble:first-of-type {
  border-bottom-right-radius: none !important;
  border-bottom-left-radius: none !important;
}
.bpw-chat-bubble:last-of-type {
  border-bottom-right-radius: none !important;
  border-bottom-left-radius: none !important;
}
.bpw-chat-bubble {
  border-radius: 25px;
  border: 2px solid orangered;
}
/* user chat bubble*/
.bpw-from-user .bpw-chat-bubble {
  background-color: orangered;
  color: #ffffff;
}
/* keyboard quick reply*/
.bpw-button {
  border: 1px solid orangered;
}
.bpw-button:hover {
  background-color: orangered;
  color: #ffffff;
  font-weight: bold;
}
