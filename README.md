# Margelet - Telegram Bots Java API

Margelet is a Java implementation to communicate with Telegram Bot API

Simple usage:

```java
Margelet margelet = new Margelet("[bot api token]");
Response<User> response = margelet.getMe();
if(response.isOk()) {
User user = response.getResult();
...
}
```

See [Telegram Bot API](https://core.telegram.org/bots/api) to know more.

```
Copyright (C) 2018 Welyab da Silva Paula

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except
in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License
is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express
or implied. See the License for the specific language governing permissions and limitations under
the License.
```
