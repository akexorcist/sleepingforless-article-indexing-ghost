# sleepingforless-article-indexing
Indexing the articles in Sleeping For Less by Ghost - https://akexorcist.dev

What's it about?
===========================
Because I'm too lazy to build the index page (https://akexorcist.dev/android-article-index) for entire articles in Sleeping For Less (https://akexorcist.dev). So I created this project to get the articles data from the Blogger API v3 into JSON then build it to HTML to replaces in index page with specific label. That's all!!

How to use it?
===========================
• Clone this project.

• Install the dependencies with `node install`

• Create the `.env` in the project to provide your Blogger ID and API Key for Blogger API v3.

```
API_KEY=YOUR_GHOST_CLIENT_API_KEY
URL=YOUR_GHOST_URL
```

• Customize the specific label for indexing in `converter.js` at `titles` (for indexing by label) and `excludes` (for exclude article by title) variables.

• Run the project with `node index | pbcopy` the HTML result will copied to your clipboard when finished.

• Do what you want.

Licence
===========================
Copyright 2020 Akexorcist

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
