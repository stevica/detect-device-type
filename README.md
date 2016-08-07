#Detect device type in Node.js

##Install and run app
 
```npm install```

```node app.js```

Hit the URL (_localhost:3000/detect_) in your browser from desktop, laptop or mobile, you should be getting output like 'Hi from {{your device}}'.

**req.device** _returns following object_

```javascript
{ parser:
    DeviceParser {
        options:
        { emptyUserAgentDeviceType: 'desktop',
            unknownUserAgentDeviceType: 'phone',
            botUserAgentDeviceType: 'bot',
            carUserAgentDeviceType: 'car',
            parseUserAgent: false 
        },
        make_sure_parser_was_executed: [Function],
            get_model: [Function],
            get_type: [Function] },
            type: 'desktop',
            name: '' 
        }
    }
}
```