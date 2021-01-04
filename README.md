# awesome
awesome
{
  "name": "coinflip",
  "permissions": "NONE",
  "restriction": "1",
  "_id": "JSpxD",
  "actions": [
    {
      "storage": "1",
      "varName": "random",
      "min": "1",
      "max": "2",
      "name": "Generate Random Number"
    },
    {
      "title": "Heads",
      "author": "",
      "color": "",
      "timestamp": "false",
      "url": "",
      "authorIcon": "",
      "imageUrl": "",
      "thumbUrl": "",
      "storage": "1",
      "varName": "heads",
      "name": "Create Embed Message"
    },
    {
      "title": "Tails",
      "author": "",
      "color": "",
      "timestamp": "false",
      "url": "",
      "authorIcon": "",
      "imageUrl": "",
      "thumbUrl": "",
      "storage": "1",
      "varName": "tails",
      "name": "Create Embed Message"
    },
    {
      "storage": "1",
      "varName": "random",
      "comparison": "1",
      "value": "1",
      "iftrue": "0",
      "iftrueVal": "",
      "iffalse": "2",
      "iffalseVal": "7",
      "name": "Check Variable"
    },
    {
      "storage": "1",
      "varName": "heads",
      "channel": "0",
      "varName2": "",
      "storage3": "0",
      "varName3": "",
      "name": "Send Embed Message"
    },
    {
      "name": "End Action Sequence"
    },
    {
      "storage": "1",
      "varName": "random",
      "comparison": "1",
      "value": "2",
      "iftrue": "0",
      "iftrueVal": "",
      "iffalse": "2",
      "iffalseVal": "4",
      "name": "Check Variable"
    },
    {
      "storage": "1",
      "varName": "tails",
      "channel": "0",
      "varName2": "",
      "storage3": "0",
      "varName3": "",
      "name": "Send Embed Message"
    },
    {
      "name": "End Action Sequence"
    }
  ],
  "comType": "0"
}


{
  "name": "funny monkey",
  "permissions": "NONE",
  "restriction": "1",
  "_id": "aIvih",
  "actions": [
    {
      "channel": "0",
      "varName": "",
      "name": "Join Voice Channel"
    },
    {
      "url": "https://www.youtube.com/watch?v=apPsjYs6HmE&ab",
      "seek": "0",
      "volume": "",
      "passes": "1",
      "bitrate": "",
      "type": "0",
      "name": "Play YouTube Video"
    }
  ],
  "comType": "1"
}



{
  "name": "funny image",
  "permissions": "SEND_MESSAGES",
  "restriction": "1",
  "_id": "IkJmo",
  "actions": [
    {
      "member": "1",
      "varName": "",
      "storage": "1",
      "varName2": "r",
      "name": "Create Image from Avatar"
    },
    {
      "storage": "1",
      "varName": "r",
      "effect": "5",
      "name": "Apply Image Effect"
    },
    {
      "storage": "1",
      "varName": "r",
      "width": "700%",
      "height": "200%",
      "name": "Resize Image"
    },
    {
      "storage": "1",
      "varName": "r",
      "channel": "0",
      "varName2": "",
      "message": "",
      "storage2": "1",
      "varName3": "r",
      "name": "Send Image"
    }
  ],
  "comType": "1"
}



{
  "name": "poo",
  "permissions": "NONE",
  "restriction": "1",
  "_id": "oaodq",
  "actions": [
    {
      "channel": "0",
      "varName": "",
      "message": "poo",
      "storage": "0",
      "varName2": "",
      "name": "Send Message"
    }
  ],
  "comType": "1"
}



{
  "name": "walter white",
  "permissions": "NONE",
  "restriction": "1",
  "_id": "wzBlx",
  "actions": [
    {
      "channel": "0",
      "varName": "",
      "message": "https://i.kym-cdn.com/photos/images/newsfeed/001/623/800/b3b.gif",
      "storage": "0",
      "varName2": "",
      "name": "Send Message"
    }
  ],
  "comType": "1"
}



{
  "name": "disconnect",
  "permissions": "NONE",
  "restriction": "1",
  "_id": "etYsh",
  "actions": [
    {
      "name": "Leave Voice Channel"
    }
  ],
  "comType": "0"
}



{
  "name": "duck song",
  "permissions": "NONE",
  "restriction": "1",
  "_id": "qPxIr",
  "actions": [
    {
      "channel": "0",
      "varName": "",
      "name": "Join Voice Channel"
    },
    {
      "url": "https://www.youtube.com/watch?v=MtN1YnoL46Q",
      "seek": "0",
      "volume": "",
      "passes": "1",
      "bitrate": "100",
      "type": "0",
      "name": "Play YouTube Video"
    }
  ],
  "comType": "1",
  "_aliases": []
}



{
  "name": "help",
  "permissions": "NONE",
  "restriction": "1",
  "_id": "JFnwA",
  "actions": [
    {
      "channel": "0",
      "varName": "",
      "message": "duck song : plays duck song in vc\nwalter white : sends walter white\npoo : says poo\n!funny image : blurred avatar\n!coinflip : heads or tails\nfunny monkey : plays funny monkey in the vc",
      "storage": "0",
      "varName2": "",
      "name": "Send Message"
    }
  ],
  "comType": "0"
}
