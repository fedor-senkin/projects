# Portfolio: QA (Test) Engineer

## About me 

My name is Fedor, I am a beginner tester.<br>
In this repository you can find some of my projects completed during internships, training and practice.<br>

## Skills and technologies
``Jira``, ``qase.io``, ``SQL``, `` Postman``, ``Swagger``, ``Trello``, <br>
``SoapUI``, ``Mockoon``, ``Chrome DevTools``, ``Miro``,  ``Android Studio``,   <br>
``Charles Proxy``
## Projects
<p> </p>

### Testing a web application for teachers from Skyeng
<p> </p>
<p>What needed to be done: test new functionality - adding personal events.<p>
  <li>Task 1. Testing requirements.</li>
  <li>Task 2. Decomposition of new functionality.</li> 
  <li>Task 3. Smoke testing.</li> 
  <li>Task 4. Functional testing at the component level (GUI, API).</li> 
  <li>Task 5. Acceptance testing.</li> 
  <li>Task 6. Regression testing.</li>
<p>
<p>How I solved it: 
<li>Requirements testing: formulations that do not meet the criteria for good requirements and questions that arose regarding them are combined in a <a href="skyeng/requirment testing.pdf">table</a>.</li>
<li><a href="skyeng/декомпозиция.jpg">Decomposition</a>were done in Miro.</li>
<li><a href="skyeng/skyeng_smoke TC.pdf">Smoke</a>, <a href="skyeng/acceptance TC.pdf">acceptance</a> and functional <a href="skyeng/skyeng_API TC.pdf">API</a> tests are designed as test cases.
<li>API test cases are made in Postman (example: <a href="skyeng/Postman.jpg">requests to create, view and delete a new event in the schedule</a>).
<li><a href="skyeng/functional tests.pdf">Functional (GUI)</a> and <a href="skyeng/regress test.pdf">regression tests</a> are designed as checklists.</li>
<li>Based on the defects identified during testing, defect reports were compiled (<a href="skyeng/bugreport1.pdf">example 1</a>, <a href="skyeng/bugreport2.pdf">example 2</a>).</li>
<p>
 <p>Results:<p>
<ol>
  <li>Learned how to create a test plan in Confluence.</li>
  <li>I can work in TMS qase.io: create functional (GUI, API) test cases, create test suites, perform test runs and analyze their results.</li>
  <li>Learned how to create low-level checklists.</li>
  <li>I know how to prepare defect reports and enter them into BTS Jira.</li>
  <li>I can work with Postman: create collections of API tests, compose requests and analyze the responses received, use variables, write simple tests using snippets.</li>
  <li>Learned to work with Chrome DevTools: analyze sent requests and received responses (URL, method, status, headers, payload), extract token from cookies, record and save log files.</li>
  <li>I know how to decompose a system.</li>
</ol>
<p> </p>

### Test documentation for testing the main page of the site <a href="https://cloud.ru/ru">Cloud.ru</a>
<p> </p>
<p>What needed to be done: create low-level checklists to test the functionality of the main page.<p>
  <p>How I solved it:  
<li>Conducted research testing of the web page, based on the results of which I compiled <a href="Cloud.ru/Cloud.ru_main page check lists.pdf">check lists</a>.</li>
<p>
 <p>Results:<p>
<ol>
  <li>I learned how to create low-level checklists based on already implemented functionality.</li>
  </ol>
<p> </p>

### Testing a mobile application for learning English from Skyeng
<p> </p>
<p>What needed to be done: conduct functional testing of the “Situations” and “Video Practice” sections.<p>
  <li>Task 1. Testing requirements.</li>
   <li>Task 2. Select an environment for testing.</li>
   <li>Task 3. Make checklists.</li>
   <li>Task 4. Conduct testing using the compiled documentation.</li>
   <li>Task 5. Substitute the response from the server to a request to display new situations.</li>
   <li>Task 6. Write a testing report.</li> 
 <p>
<p>How I solved it: 
<li>Requirements testing: formulations that do not meet the criteria for good requirements and questions that arose regarding them are combined in a <a href="Skyeng mobile/Requirement testing.pdf">table</a>.</li>
<li>The selection of the environment for testing was carried out on the basis of the provided statistical data and is presented in the form of a <a href="Skyeng mobile/Test environment.pdf">table</a>.</li>
<li>Prepared<a href="Skyeng mobile/Checklists_mobile.pdf">checklists</a> based on the provided documentation.</li>
<li>Testing carried out on <a href="Skyeng mobile/Android Studio.png"> an emulator</a> in Android Studio.</li>
<li>The response was replaced using the Charles Proxy traffic sniffer using the Breakpoints function (<a href="Skyeng mobile/Response breakpoint.pdf">an example of using the tool</a>).</li>
<li>Based on the testing results, a <a href="Skyeng mobile/Test report_mobile.pdf">report was compiled</a> (<a href="Skyeng mobile/Bag reports_example.pdf">examples of bug reports</a>)</li>
<p>
 <p>Results:<p>
<ol>
  <li>Learned how to work with Android Studio: select and configure an emulator, conduct functional testing of a mobile application, perform special checks for mobile applications.</li>
  <li>I know how to install APK files on emulators in Android Studio.</li>
  <li>I learned how to work with the Charles Proxy traffic sniffer: I can analyze traffic, intercept requests and replace them.</li>
  </ol>
  <p> </p>
  
### Investment platform <a href="https://zorko-exchange.ru/">Zorko</a> 
<p>Worked full time as a part of a testing team: team lead + 4 testers.</p>
<p> </p>
<p>What needed to be done: test the website of the Zorko investment platform.<p>
   <li>Task 1. Create checklists.<p>How I solved it: <a href="Zorko/Zorko_checklist.jpg">checklists</a> were compiled in Miro.</p></li>
   <li>Task 2. Test UX/UI of the site layout (mobile and web versions). <p>How I decided: I was responsible for testing the layout in the web version on a Windows device in the Chrome browser, the mobile version on an Android device in the Firefox browser for compliance with the layouts in Figma.</p></li>
   <li>Task 3. Test the functionality of registering a new user and assigning him a confirmed investor status (KYC). <p>How I solved it: I registered two new test users in the system, who were assigned KYC status through the admin panel.</p></li>
   <li>Task 4. Test the functionality of selling/purchasing shares. <p>How I decided: on behalf of the first test user I placed shares on the market for sale, on behalf of the second one I placed an order to buy shares on the market.</p></li>
   <p>
<p>Results:<p>
<ol>
   <li>Found 12 bugs (including 2 blockers).</li>
   <li>For each defect a bug report were created in ClickUp .</li>
   <li>Added 1 suggestion to improve the UI.</li>
   <li>The result of the work was conveyed to the developer during a call via Google Meet.</li>
  </ol>
<p> </p>

### Mobile application for relocants KetchUp
<p>Worked full time as part of a testing team: team lead + 3 testers.</p>
<p> </p>
<p>What had to be done: test the KetchUp mobile application for relocants, which unites people by interests in a new place of residence.<p>
   <li>Task 1. Create checklists.<p>How I solved it: I compiled checklists in Miro.</p></li>
   <li>Task 2. Test the implementation for compliance with layouts in Figma.<p>How I solved it: I was responsible for testing the interface on an Android 10 device for compliance with layouts in Figma.</p></li>
   <li>Task 3. Test the functionality of registering/authorizing of a new user.<p>How I solved it: registered a new test user in the system, then logged in.</p></li>
   <li>Task 4. Test the functionality of creating events and groups.<p>How I solved it: created an event and a group on behalf of a test user; checked the availability of information about the date/time of the event and the topic of the group to other users; the opportunity to register for an event or join a group; the ability to post images in the event/group photo gallery; exchanging messages in the group chat.</p></li>
   <li>Task 5. Test the functionality of messaging with other users.<p>How I solved it: I tested adding other users as friends and exchanging messages between them, text messages and images.</p></li>
   <p>
<p>Results:<p>
<ol>
   <li>Found 25 bugs (including 3 blockers).</li>
   <li>I created a bug report in ClickUp for each defect.</li>
   <li>Added 3 suggestions to improve the UI.</li>
   <li>The result of the work was conveyed to the developer during a call in Google Meet.</li>
  </ol>
<p> </p>

## Contacts
- Telegram: https://t.me/fedorsenkin
