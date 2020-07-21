# add-event-to-calendar

Generate invitation calendar link.

## Calendar support
1. Google Calendar
2. Microsoft Outlook
3. Yahoo! Calendar
4. Apple Calendar
5. Download .ics are done through the iCal format

## Features
1. Isomorphic library
2. Zero dependencies
3. Typescript declararactions

## Install

npm:
```
npm install add-event-to-calendar
```

yarn:
```
yarn add add-event-to-calendar
```
 
## Usage example

```typescript
import makeUrl, { TCalendarEvent } from 'add-event-to-calendar';

const getCalendarEvent = (lesson: TPrivateLesson): TCalendarEvent => ({
   name: `Event name`,
   location: 'Event location',
   details: `Event details`,
   startsAt: 'Event start at',
   endsAt: 'Event end at,
 });
 
 const eventUrls = makeUrls(event);
```

## License
 
The MIT License (MIT)

Copyright (c) 2020 Viacheslav Borodulin

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
