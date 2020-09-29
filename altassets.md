---


---

<h1 id="overview">Overview</h1>
<p>When PENSCO receives requests from clients and asset sponsors regarding alternative assets, those requests have requirements regarding information, documents, checklists, and review. The Alt Assets Admin (AAA) app automates some of the workflow and processing tasks for creating new Assets, Commitments, New Purchases, Capital Calls, Exchanges, and Additional Purchases. AAA also integrates workflow with Transfers Admin (TA) to process any alt assets contained in incoming Transfers.</p>
<p>Requests arrive via mail/email/fax and are received by the Doc Services (DS) team members, who scan the documents and/or upload them to Doc Queue.  From there, the DS and the Private Equity (PE) teams both have the ability to use them to create requests in AAA, which can then be assigned to specific processors.</p>
<p>PE processors can view and search their own work queue and the queues of the rest of their team. Processors can open requests, gather the required information and documents, check off items on the checklist of requirements for that request type, and finally send the request to Quality Control (QC). QC can Accept or Return the request to the original processor and add notes if needed. If the request involves a transaction greater than $300,000, another reviewer – QC2 – reviews the requests and either Accepts or Returns it to the original processor.</p>
<p>Once the request is Accepted by QC (and QC2 where needed), its path varies by request type:</p>
<ul>
<li><strong>Assets</strong> - Information is sent to Innotrust, and then the processor marks the request Complete.</li>
<li><strong>Commitments</strong> - The processor prints and sends any necessary documents to the client or asset sponsor, and then marks the request Complete.</li>
<li><strong>New Purchases</strong> - Information is sent to Innotrust, the processor prints/sends out documents, waits for the signed confirmation documents to be returned, and then marks the request Complete.</li>
<li><strong>Capital Calls</strong> - Information is sent to Innotrust, and then the processor marks the request Complete.</li>
<li><strong>Additional Purchases</strong> -  Information is sent to Innotrust, the processor prints/sends out documents, and then marks the request Complete.</li>
<li><strong>Exchanges</strong> -  Information is sent to Innotrust, the processor prints/sends out documents, and then marks the request Complete.</li>
<li><strong>Transfer Reviews</strong> - The processor prints/sends out documents, and then marks the request Complete, enabling it to continue its path through the Transfers Admin workflow.</li>
</ul>
<p>Users also have the ability to add new sponsors, and admins have the ability to set permissions and the roles of other users.</p>
<p>System Context Diagram</p>
<p>Cross-functional workflow diagram</p>
<h1 id="accessing-alt-assets">Accessing Alt Assets</h1>
<p>Access the application at <a href="https://apps.pensco.net/alt-asset-admin">https://apps.pensco.net/alt-asset-admin</a>. Chrome is the recommended browser.  As a PENSCO employee, you can sign in with your network login credentials.</p>
<p>After login, the first screen is My Queue, which lists all trades currently assigned to the user.</p>
<p>From anywhere in the application, you can return to the homepage by clicking the Alt Asset logo in the upper left corner.</p>
<h1 id="user-roles-and-views">User roles and views</h1>
<p>When you view the Alt Assets home page, your user role defines what options are available to you. The user roles are Inquiry, Create, Review, Accept, Maintain, and Admin.</p>
<h2 id="inquiry-role">Inquiry role</h2>
<p>The Inquiry role can search, view assets, view requests, and add notes.</p>
<p>Inquiry permissions are given to all users by default.  If you need additional access, contact an admin in the Alt Assets group.</p>
<h2 id="create-role-–-not-yet-impemented">Create role – NOT YET IMPEMENTED</h2>
<p>The Create role has all Inquiry capabilities but can also create client requests and manage documents.</p>
<h2 id="review-role">Review role</h2>
<p>The Review role has all Create capabilities but can also review asset and client requests.</p>
<h2 id="accept-role">Accept role</h2>
<p>The Accept role has all Review capabilities but can also provide the additional QC review required for large transactions.</p>
<p>When an item is “In QC” status, opening the item shows Create and Accept buttons. The accept dropdown includes Return, Cancel, and Reject.</p>
<h2 id="maintain-role-–-not-yet-impemented">Maintain role – NOT YET IMPEMENTED</h2>
<p>The Maintain role has all Inquiry capabilities but with additional edit permissions for accepted assets and completed requests.</p>
<h2 id="admin-role">Admin role</h2>
<p>The Admin role has all capabilities in the other roles plus the ability to change roles for other team members.</p>
<h1 id="search">Search</h1>
<p>The alt assets Search tool can find partial matches for asset name, CUSIP, account number, and sponsor name.  Also, you can limit search results using filter checkboxes.</p>
<p>When search results display, you can open any item with a double-click.</p>
<h1 id="asset-detail-screen">Asset Detail screen</h1>
<p>The Asset Detail screen displays information about the asset, the asset sponsor, the supporting documentation, checklists, and notes about key lifecycle changes. Also displayed is a list of requests currently in process regarding this asset, and a list of the account currently holding the asset.</p>
<p>The In Progress list includes Create buttons from which New Purchase and Commitment requests can be initiated.</p>
<p>The Current Holders list includes Start buttons from which Additional Purchases, Exchanges, and Capital Calls can be initiated.</p>
<h1 id="request-type-workflows">Request Type Workflows</h1>
<p>Workflow varies for each request type: Commitment, New Purchase, Additional Purchase, Capital Call, Exchange, Asset, and Transfer Review.</p>
<h2 id="commitments">Commitments</h2>
<p>Processors can start a commitment-only client request.</p>
<p>On the Asset Detail screen, the processor chooses <strong>Create &gt; Commitment</strong>, and the Start New Commitment screen displays:</p>
<p>On the Start New Commitment screen, the processor completes the required fields and clicks <strong>Create Request</strong>. The system validates required fields are completed:</p>
<ul>
<li>Asset</li>
<li>Account #</li>
</ul>
<p>If validation fails, the processor sees a message detailing the failed validation, and they are returned to the Create screen.  If validation succeeds, the request moves into IN REVIEW status, causing it to appear in the processor’s queue.</p>
<p><strong>Status: IN REVIEW</strong><br>
The processor sees the request in their queue, and double-clicks to open it in the Review screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>SendToQC</strong> - Moves the request into QC status.</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p>The processor enters the Funding Method information, uploads and accepts Documents, answers the Checklist questions, and clicks <strong>SendToQC</strong>. The system validates:</p>
<ul>
<li>Asset(s) have status of QC, Processing, or Accepted.</li>
<li>Request has a Funding Method, and the method’s related fields are completed</li>
<li>Related account is open in ODS</li>
<li>All docs are present and accepted</li>
<li>All checklist question are satisfied</li>
</ul>
<p>If validation fails, the processor sees a message detailing the validations that have failed, and they are returned to the Review page. The request remains in IN REVIEW status and remains in the processor’s queue.</p>
<p>If validation succeeds, the request moves into QC status.</p>
<p><strong>Status: QC</strong><br>
When the request enters QC status, it is unassigned. The QC processor sees the request in their queue, and either assigns it to another QC processor or opens it in the QC screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>Accept</strong> - Moves the request into EXECUTION status.</li>
<li><strong>Return to Reviewer</strong> - Moves the request to IN REVIEW status and reassigns it to the initial reviewer.</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p>When the QC processor clicks <strong>Accept</strong>, the system validates that the asset is in ACCEPTED status, and then moves the request into EXECUTION status.</p>
<p><strong>Status: EXECUTION</strong><br>
The initial processor sees the request in their queue in EXECUTION status and then has time to print/send any necessary documents.  Once the documents are sent (or If no documentation is needed), the processor clicks <strong>Complete</strong>, moving the request into COMPLETE status.</p>
<p>Available actions:</p>
<ul>
<li><strong>Complete</strong> - Moves the request into COMPLETE status.</li>
</ul>
<p><strong>Status: COMPLETE</strong><br>
This is the happy-path end state.</p>
<p><strong>Exception States</strong></p>
<ul>
<li>Status: REJECT - From IN REVIEW or QC status, the processor or QC manager can Reject the request</li>
<li>Status: CANCEL - From IN REVIEW or QC status, the processor or QC manager can Cancel the request.<br>
<img src="https://github.com/jstonecypher/docs/blob/master/AltAssets-Commitment.png" alt="enter image description here"></li>
</ul>
<h2 id="new-purchases">New Purchases</h2>
<p>Processors can start a new purchase for an asset a client does not currently own.</p>
<p>On the Asset Detail screen, the processor chooses <strong>Create &gt; Purchase</strong>, and the Start New Purchase screen displays.</p>
<p>On the Start New Purchase screen, the processor completes the required fields and clicks <strong>Create Request</strong>. The system validates required fields are completed:</p>
<ul>
<li>Asset</li>
<li>Account #</li>
</ul>
<p>If validation fails, the processor sees a message detailing the failed validation, and they are returned to the Create screen.  If validation succeeds, the request moves into IN REVIEW status, causing it to appear in the processor’s queue.</p>
<p><strong>Status: IN REVIEW</strong></p>
<p>The processor sees the request in their queue, and double-clicks to open it in the Review screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>SendToQC</strong> - Moves the request into QC status.</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p>The processor enters the Funding Method information, uploads and accepts Documents, answers the Checklist questions, and clicks <strong>SendToQC</strong>. The system validates:</p>
<ul>
<li>Request has a Funding Method, and the method’s related fields are completed</li>
<li>Related account is open in ODS</li>
<li>Related account has enough cash</li>
<li>All docs are present</li>
<li>All docs are accepted</li>
<li>All checklist question are satisfied</li>
</ul>
<p>If validation fails, the processor sees a message detailing the validations that have failed, and they are returned to the Review page. The request  remains in IN REVIEW status and remains in the processor’s queue.</p>
<p>If validation succeeds, the request moves into QC status.</p>
<p><strong>Status: QC</strong></p>
<p>When the request enters QC status, it is unassigned. The QC processor sees the request in their queue, and either assigns it to another QC processor or opens it in the QC screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>Accept</strong> (This action is available only if the amount is less than $300,000) - Moves the request into PROCESSING status.</li>
<li><strong>SendToQC</strong> (This action is available only if the amount is greater than $300,000) - Moves the request into QC2 status.</li>
<li><strong>Return</strong> - Moves the request back into IN REVIEW status</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p>When the QC processor clicks <strong>Accept</strong> or <strong>SendToQC</strong>, the system validates that the asset is in ACCEPTED status, and then moves the request into EXECUTION or QC2 status.</p>
<p><strong>Status: QC2</strong></p>
<p>Requests go through this status only if the amount is greater than $300,000. In such instances, the first QC cannot accept the request; they can only <strong>SendToQC</strong>, moving it to QC2 status.</p>
<p>When the request enters QC2 status, it is unassigned. The QC2 processor sees the request and either assigns it to another QC processor or opens it in the QC screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>Accept</strong> - Moves the request into PROCESSING status.</li>
<li><strong>Return</strong> - Moves the request chase back into IN REVIEW status.</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p><strong>Status: PROCESSING</strong></p>
<p>Requests go into this status after QC or QC2 accept the request.  In PROCESSING status, the request is sent to Innotrust (BuyRec and Disbursement) and then automatically moved into EXECUTION status, causing it to appear in the processor’s queue.</p>
<p><strong>Status: EXECUTION</strong></p>
<p>The initial processor sees the request in their queue in EXECUTION status and then has time to print/send any necessary documents.  Once the documents are sent (or If no documentation is needed), the processor clicks <strong>Awaiting Confirmation</strong>, moving the request into PENDING CONFIRMATION status.</p>
<p><strong>Status: PENDING CONFIRMATION</strong></p>
<p>Once documents have been received from the client (or if no documentation is needed), the processor clicks <strong>Complete</strong>, moving the request into COMPLETE status, and sending an update to Innotrust to move the shares from PENDING to BOOK SHARES.</p>
<p>Pending Confirmation is the equivalent of Follow-Up.</p>
<p>Available actions:</p>
<ul>
<li><strong>Complete</strong> - Moves the request into COMPLETE status.</li>
<li><strong>Resign</strong> - Moves the request into RESIGNED status (This is not common).</li>
</ul>
<p><strong>Status: COMPLETE</strong></p>
<p>This is the happy-path end state.</p>
<p><strong>Exception States</strong></p>
<ul>
<li>Status: REJECT - From IN REVIEW, QC, or QC2 status, the processor or QC manager can Reject the request.</li>
<li>Status: CANCEL - From IN REVIEW, QC, or QC2 status, the processor or QC manager can Cancel the request.</li>
<li>Status: RESIGNED - From PENDING CONFIRMATION status, the processor can RESIGN the request, sending it to an end state of RESIGNED.</li>
</ul>
<h2 id="capital-calls">Capital Calls</h2>
<p>Processors can start Cap Calls for an asset that a client already owns.</p>
<p>On the Asset Detail screen, the processor chooses <strong>Start &gt; Capital Call</strong>, and the Start New Capital Call screen displays:</p>
<p>On the Start New Capital Call screen, the processor completes the required fields and clicks <strong>Create Request</strong>. The system validates required fields are completed:</p>
<ul>
<li>Asset</li>
<li>Account #</li>
</ul>
<p>If validation fails, the processor sees a message detailing the failed validation, and they are returned to the Create screen.  If validation succeeds, the request moves into IN REVIEW status.</p>
<p><strong>Status: IN REVIEW</strong></p>
<p>The processor sees the request in their queue, and double-clicks to open it in the Review screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>SendToQC</strong> - Moves the request into QC status.</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p>The processor enters the Funding Method information, uploads and accepts Documents, answers the Checklist questions, and clicks <strong>SendToQC</strong>. The system validates:</p>
<ul>
<li>Asset(s) have status of QC, Processing, or Accepted.</li>
<li>Request has a Funding Method, and the method’s related fields are completed</li>
<li>Related account is open in ODS</li>
<li>Related account has enough cash</li>
<li>All docs are present</li>
<li>All docs are accepted</li>
<li>All checklist question are satisfied</li>
</ul>
<p>If validation fails, the processor sees a message detailing the validations that have failed, and they are returned to the Review page. The request remains in IN REVIEW status and remains in the processor’s queue.</p>
<p>If validation succeeds, the request moves into QC status.</p>
<p><strong>Status: QC</strong></p>
<p>When the request enters QC status, it is unassigned. The QC processor sees the request in their queue, and either assigns it to another QC processor or opens it in the QC screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>Accept</strong> (This action is available only if the amount is less than $300,000) - Moves the request into PROCESSING status.</li>
<li><strong>SendToQC</strong> (This action is available only if the amount is greater than $300,000) - Moves the request into QC2 status.</li>
<li><strong>Return</strong> - Moves the request back into IN REVIEW status</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p>When the QC processor clicks <strong>Accept</strong> or <strong>SendToQC</strong>, the system validates that the asset is in ACCEPTED status, and then moves the request into EXECUTION or QC2 status.</p>
<p><strong>Status: QC2</strong></p>
<p>Requests go through this status only if the amount is greater than $300,000. In such instances, the first QC cannot accept the request; they can only <strong>SendToQC</strong>, moving it to QC2 status.</p>
<p>When the request enters QC2 status, it is unassigned. The QC2 processor sees the request and either assigns it to another QC2 processor or opens it in the QC screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>Accept</strong> - Moves the request into PROCESSING status.</li>
<li><strong>Return</strong> - Moves the request back into IN REVIEW status.</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p><strong>Status: PROCESSING</strong></p>
<p>Requests go into this status after QC or QC2 accept the request.  In PROCESSING status, the request is sent to Innotrust (Disbursement) and then automatically moved into COMPLETE status.</p>
<p><strong>Status: COMPLETE</strong></p>
<p>This is the happy-path end state.</p>
<p><strong>Exception States</strong></p>
<ul>
<li>Status: REJECT - From IN REVIEW, QC, or QC2 status, the processor or QC manager can <strong>Reject</strong> the request</li>
<li>Status: CANCEL - From IN REVIEW, QC, or QC2 status, the processor or QC manager can <strong>Cancel</strong> the request.</li>
</ul>
<h2 id="additional-purchase">Additional Purchase</h2>
<p>Processors can start additional purchases for an asset the client already owns.</p>
<p>On the Asset screen, the processor chooses <strong>Start &gt; Additional Purchase</strong>.</p>
<p>On the Start Additional Purchase page, the processor completes the required fields and clicks <strong>Create Request</strong>. The system validates required fields are completed:</p>
<ul>
<li>Asset</li>
<li>Account #</li>
</ul>
<p>If validation fails, the processor sees a message detailing the failed validation, and they are returned to the Create screen.  If validation succeeds, the request moves into IN REVIEW status.</p>
<p><strong>Status: IN REVIEW</strong></p>
<p>The processor sees the request in their queue, and double-clicks to open it in the Review screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>SendToQC</strong> - Moves the request into QC status.</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p>The processor enters the Funding Method information, uploads and accepts Documents, answers the Checklist questions, and clicks <strong>SendToQC</strong>. The system validates:</p>
<ul>
<li>Asset(s) have status of QC, Processing, or Accepted.</li>
<li>Request has a Funding Method, and the method’s related fields are completed</li>
<li>Related account is open in ODS</li>
<li>Related account has enough cash</li>
<li>All docs are present</li>
<li>All docs are accepted</li>
<li>All checklist question are satisfied</li>
</ul>
<p>If validation fails, the processor sees a message detailing the validations that have failed, and they are returned to the Review page. The request remains in IN REVIEW status and remains in the processor’s queue.</p>
<p>If validation succeeds, the request moves into QC status.</p>
<p><strong>Status: QC</strong></p>
<p>When the request enters QC status, it is unassigned. The QC processor sees the request in their queue, and either assigns it to another QC processor or opens it in the QC screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>Accept</strong> (This action is available only if the amount is less than $300,000) - Moves the request into PROCESSING status.</li>
<li><strong>SendToQC</strong> (This action is available only if the amount is greater than $300,000) - Moves the request into QC2 status.</li>
<li><strong>Return</strong> - Moves the request back into IN REVIEW status</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p>When the QC processor clicks <strong>Accept</strong> or <strong>SendToQC</strong>, the system validates that the asset is in ACCEPTED status, and then moves the request into EXECUTION or QC2 status.</p>
<p><strong>Status: QC2</strong></p>
<p>Requests go through this status only if the amount is greater than $300,000. In such instances, the first QC cannot accept the request; they can only <strong>SendToQC</strong>, moving it to QC2 status.</p>
<p>When the request enters QC2 status, it is unassigned. The QC2 processor sees the request and either assigns it to another QC processor or opens it in the QC screen.</p>
<p>Available Actions:</p>
<ul>
<li><strong>Accept</strong> - Moves the request into PROCESSING status.</li>
<li><strong>Return</strong> - Moves the request back into IN REVIEW status.</li>
<li><strong>Reject</strong> - Moves the request into REJECT status.</li>
<li><strong>Cancel</strong> - Moves the request into CANCEL status.</li>
</ul>
<p><strong>Status: PROCESSING</strong></p>
<p>Requests go into this status after QC or QC2 accept the request.  In PROCESSING status, the request is sent to Innotrust (BuyRec and Disbursement) and then automatically moved into EXECUTION status, causing it to appear in the processor’s queue.</p>
<p><strong>Status: EXECUTION</strong></p>
<p>The initial processor sees the request in their queue in EXECUTION status and then has time to print/send any necessary documents.  Once the documents are sent (or If no documentation is needed), the processor clicks <strong>Complete</strong>, moving the request into COMPLETE status.</p>
<p><strong>Status: COMPLETE</strong></p>
<p>This is the happy-path end state.</p>
<p><strong>Exception States</strong></p>
<ul>
<li>Status: REJECT - From IN REVIEW, QC, or QC2 status, the processor or QC manager can <strong>Reject</strong> the request</li>
<li>Status: CANCEL - From IN REVIEW, QC, or QC2 status, the processor or QC manager can <strong>Cancel</strong> the request.</li>
</ul>
<h2 id="exchanges">Exchanges</h2>
<p>Processors can create exchange requests to exchange one asset for another.</p>
<p>On the Asset screen, the processor chooses Start &gt; Exchange.</p>
<p>On the Start New Exchange page, the processor completes the required fields and clicks Create Request. The system validates required fields are completed:</p>
<ul>
<li>Asset</li>
<li>Account #</li>
</ul>
<p>If validation fails, the processor sees a message detailing the failed validation, and they are returned to the Create screen.  If validation succeeds, the request moves into IN REVIEW status.</p>
<p><strong>Status: IN REVIEW</strong></p>
<p>The processor sees the request in their queue, and double-clicks to open it in the Review screen.</p>
<p>Available Actions:</p>
<ul>
<li>SendToQC - Moves the request into QC status.</li>
<li>Reject - Moves the request into REJECT status.</li>
<li>Cancel - Moves the request into CANCEL status.</li>
</ul>
<p>The processor enters the Funding Method information, uploads and accepts Documents, answers the Checklist questions, and clicks SendToQC. The system validates:</p>
<ul>
<li>Asset(s) have status of QC, Processing, or Accepted.</li>
<li>Request has a Funding Method, and the method’s related fields are completed</li>
<li>Related account is open in ODS</li>
<li>Client holds enough booked shares to exchange from (greater than or equal to the amount of shares listed for the from asset)</li>
<li>All docs are present</li>
<li>All docs are accepted</li>
<li>All checklist question are satisfied</li>
</ul>
<p>If validation fails, the processor sees a message detailing the validations that have failed, and they are returned to the Review page. The request remains in IN REVIEW status and remains in the processor’s queue.</p>
<p>If validation succeeds, the request moves into QC status.</p>
<p><strong>Status: QC</strong></p>
<p>When the request enters QC status, it is unassigned. The QC processor sees the request in their queue, and either assigns it to another QC processor or opens it in the QC screen.</p>
<p>Available Actions:</p>
<ul>
<li>Accept - Moves the request into PROCESSING status.</li>
<li>Return - Moves the request back into IN REVIEW status</li>
<li>Reject - Moves the request into REJECT status.</li>
<li>Cancel - Moves the request into CANCEL status.</li>
</ul>
<p>When the QC processor clicks Accept, the system validates that the asset is in ACCEPTED status, and then moves the request into PROCESSING status.</p>
<p><strong>Status: PROCESSING</strong></p>
<p>Requests go into this status after QC accepts the request.  In PROCESSING status, the request is sent to Innotrust (RFP and DFP)  and then automatically moved into EXECUTION status, causing it to appear in the processor’s queue.</p>
<p><strong>Status: EXECUTION</strong></p>
<p>The initial processor sees the request in their queue in EXECUTION status and then has time to print/send any necessary documents.  Once the documents are sent (or If no documentation is needed), the processor clicks Complete, moving the request into COMPLETE status.</p>
<p><strong>Status: COMPLETE</strong></p>
<p>This is the happy-path end state.</p>
<p><strong>Exception States</strong></p>
<ul>
<li>Status: REJECT - From IN REVIEW or QC status, the processor or QC manager can Reject the request</li>
<li>Status: CANCEL - From IN REVIEW or QC status, the processor or QC manager can Cancel the request.</li>
</ul>
<h2 id="assets">Assets</h2>
<p>When sponsors request for an asset to be held at PENSCO, processors can add the asset and trigger the asset review process.</p>
<p>On the AAA main toolbar, the processor chooses Create Asset.</p>
<p>On the Find or Create an Asset screen, the processor starts entering the asset name or CUSIP, and a dropdown auto-populates with possible matches with assets that already exist in PENSCO, and also provides an Add New Asset option to create new ones.  Select an asset to open it, or click Add New Asset to go to the Create New Asset screen.</p>
<p>On the Create New Asset screen, the processor completes the required fields and clicks Create. The system validates required fields are completed:</p>
<ul>
<li>Name</li>
<li>Category</li>
</ul>
<p>If validation fails, the processor sees a message detailing the failed validation, and they are returned to the Create screen.  If validation succeeds, the request moves into IN REVIEW status, causing it to appear in the processor’s queue.</p>
<p><strong>Status: IN REVIEW</strong></p>
<p>The processor sees the request in their queue, and double-clicks to open it in the Review screen.</p>
<p>Available Actions:</p>
<ul>
<li>SendToQC - Moves the request into QC status.</li>
<li>Reject - Moves the request into REJECT status.</li>
<li>Cancel - Moves the request into CANCEL status.</li>
</ul>
<p>The processor enters the information, uploads and accepts Documents, answers the Checklist questions, and clicks SendToQC. The system validates:</p>
<ul>
<li>Name</li>
<li>Sponsor</li>
<li>Structure Type</li>
<li>Stock Preferred (if Structure Type is corporation)</li>
<li>Ownership Type (if Structure Type is LLC)</li>
<li>Pricing Method</li>
<li>Price Value (if Pricing Method is Price Per Share)</li>
<li>All docs are present and accepted</li>
<li>All checklist question are satisfied</li>
</ul>
<p>If validation fails, the processor sees a message detailing the validations that have failed, and they are returned to the Review page. The request remains in IN REVIEW status and remains in the processor’s queue.</p>
<p>If validation succeeds, the request moves into QC status.</p>
<p><strong>Status: QC</strong></p>
<p>When the request enters QC status, it is unassigned. The QC processor sees the request in their queue, and either assigns it to another QC processor or opens it in the QC screen.</p>
<p>Available Actions:</p>
<ul>
<li>Return - Moves the request back into IN REVIEW status</li>
<li>Reject - Moves the request into REJECT status.</li>
<li>Cancel - Moves the request into CANCEL status.</li>
</ul>
<p>When the QC processor clicks Accept, the system validates that the asset is in ACCEPTED status, and then moves the request into PROCESSING status.</p>
<p><strong>Status: PROCESSING</strong></p>
<p>Requests go into this status after QC accepts the request.  In PROCESSING status, the request is sent to Innotrust (creating security and price). When processing completes, the request is moved automatically to ACCEPTED status.</p>
<p><strong>Status: ACCEPTED</strong></p>
<p>This is the happy-path end state.</p>
<p><strong>Exception States</strong></p>
<ul>
<li>Status: REJECT - From IN REVIEW or QC status, the processor or QC manager can Reject the request</li>
<li>Status: CANCEL - From IN REVIEW or QC status, the processor or QC manager can Cancel the request.</li>
</ul>
<h2 id="transfer-review">Transfer Review</h2>
<p>When the Transfers Admin (TA) app receives an incoming transfer which contains alternative assets, those assets go into IN REVIEW status, which includes them in the Alt Assets Admin (AAA) workflow, in which the processor can review the account and asset combination.</p>
<p><strong>Status: IN REVIEW</strong></p>
<p>The processor who started the transfer then finds the transfer in AAA and either assigns it to another processor or double-clicks to open it in the Review screen.</p>
<p>Available Actions:</p>
<ul>
<li>SendToQC - Moves the request into QC status.</li>
<li>Reject - Moves the request into REJECT status.</li>
<li>Cancel - Moves the request into CANCEL status.</li>
</ul>
<p>The processor enters the information, uploads and accepts Documents, answers the Checklist questions, and clicks SendToQC. The system validates:</p>
<ul>
<li>Asset is in ACCEPTED status.</li>
<li>All docs are present and accepted</li>
<li>All checklist question are satisfied</li>
</ul>
<p>If validation fails, the processor sees a message detailing the validations that have failed, and they are returned to the Review page. The request remains in IN REVIEW status and remains in the processor’s queue.</p>
<p>If validation succeeds, the request moves into QC status.</p>
<p><strong>Status: QC</strong></p>
<p>When the request enters QC status, it is unassigned. The QC processor sees the request in their queue, and either assigns it to another QC processor or opens it in the QC screen.</p>
<p>Available Actions:</p>
<ul>
<li>Accept - Moves the request into EXECUTION status.</li>
<li>Return - Moves the request back into IN REVIEW status</li>
<li>Reject - Moves the request into REJECT status.</li>
<li>Cancel - Moves the request into CANCEL status.</li>
</ul>
<p>When the QC processor clicks Accept, the system validates that the asset is in ACCEPTED status, and then moves the request into EXECUTION status.</p>
<p><strong>Status: EXECUTION</strong></p>
<p>The initial processor sees the request in their queue in EXECUTION status and then has time to print/send any necessary documents.  Once the documents are sent (or If no documentation is needed), the processor clicks Complete, moving the request into COMPLETE status.</p>
<p><strong>Status: COMPLETE</strong></p>
<p>This is the happy-path end state for the request’s flow through the AAA app, allowing the asset request to proceed through the Transfer Admin (TA) workflow. Once in this end state, a note is sent to the Transfers-In team.</p>
<p><strong>Exception States</strong></p>
<ul>
<li>Status: REJECT - From IN REVIEW or QC status, the processor or QC manager can Reject the request. Once in this end state, a note is sent to the Transfers-In team.</li>
<li>Status: CANCEL - From IN REVIEW or QC status, the processor or QC manager can Cancel the request. Once in this end state, a note is sent to the Transfers-In team.</li>
</ul>
<h1 id="create-asset">Create Asset</h1>
<p>See section 6.6 - Assets</p>
<h1 id="asset-sponsors">Asset Sponsors</h1>
<p>The Asset Sponsors functionality allows you to find, add, and manage asset sponsors.</p>
<h2 id="asset-sponsors-list">Asset Sponsors List</h2>
<p>Select Asset Sponsors from the main header, and the Asset Sponsors screen displays the list of sponsors (showing Sponsor Name, TIN, and state) currently in the system. You can filter the list by typing in part of the sponsor name.</p>
<p>In header, select Asset Sponsors to see list of all asset sponsors.</p>
<p>Use the filter bar to type and find a specific sponsor. Click on the sponsor name to go to the detail page.</p>
<p>If the sponsor is not in the system, you can also + Add New Sponsor.</p>
<h2 id="sponsor-detail">Sponsor Detail</h2>
<p>The Sponsor Detail screen allows you to view sponsor info, edit contact information, and add individual contacts.</p>
<p>Components:</p>
<ul>
<li>Sponsor Info</li>
<li>Assets (list of all pending and accepted Assets associated with Sponsor)</li>
<li>Contacts (individual contacts associated with the overall Sponsor entity)</li>
</ul>
<h2 id="add-sponsor">Add Sponsor</h2>
<p>On the Sponsor Detail screen, choose + Add New Sponsor, and the New Sponsor modal displays. Just sponsor name is required. Make sure to use a unique TIN to make sure it sends to Innotrust.</p>
<h1 id="status-management">Status Management</h1>
<p>Alt Assets Admin manages workflow processing by putting client requests through an ordered series of states until reaching a completion state. The current state determines what options are available to users.</p>
<p>All client requests start in IN REVIEW status, go through either one or two QC states. Unless they are canceled or rejected, they eventually reach an end state (ACCEPTED for assets, or COMPLETE for all other requests).</p>
<p>After QC and before completion, requests follow a variety of paths based on request type. Some requests have a PROCESSING state during which data is sent to Innotrust.  Some requests have an EXECUTION state which gives processors time to print and send any necessary documents to clients.</p>
<p>Because new purchases require a signed confirmation from the sponsor, they have an additional state for PENDING CONFIRMATION. For the rare instance when the confirmation is not received, there is also a RESIGN state.</p>
<h2 id="alt-asset-client-request-states">Alt asset client request states</h2>
<p><strong>STATUS: None</strong> - While the request is being created (and therefore doesn’t have a status yet), minimal information is required to be able to click the Create button.</p>
<p><strong>STATUS: In Review</strong> - The request has been created, and a processor is gathering information and documents to prepare for submission. Options Available: SendToQC, Cancel, Reject</p>
<p><strong>STATUS: QC</strong> - The request has been submitted and needs approval. For new purchases, additional purchases, and cap calls greater than $300k, a second QC review is required, so Accept is replaced with SendToQC. Options Available: Accept, SendToQC, Return, Cancel, Reject</p>
<p><strong>STATUS: QC2</strong> - This status occurs only for new purchases, additional purchases, and cap calls greater than $300k. Return sends the request back to the original processor. Accept sends commitments and transfer reviews into EXECUTION status; and sends new purchases, additional purchases, cap calls, exchanges, and assets to PROCESSING status. Options Available: Accept, Return, Cancel, Reject</p>
<p><strong>STATUS: Processing</strong> - The request has been approved, and data is being sent to Innotrust. Once data is sent and processing is complete: 1). New purchases, additional purchases, and exchanges go automatically into EXECUTION status. 2). Cap calls go automatically into COMPLETE status, and 3). Assets go automatically into ACCEPTED status. Processing status is not applicable to commitments and transfer reviews. Options Available: None</p>
<p><strong>STATUS: Execution</strong> - Commitments, new purchases, additional purchases, exchanges, and transfer reviews sit in this status while processors print/send any necessary documents to clients. Once documents are printed/sent, the processor clicks Awaiting Confirmation (for new purchases) or Complete (for other request types). Not applicable to assets and cap calls. Options Available: Complete, Awaiting Confirmation</p>
<p><strong>STATUS: Pending Confirmation</strong> - This new purchase request is waiting for signed confirmation documents from the sponsor. Once documents are received, the processor clicks Complete. In the rare case where the documents never come, the processor can Resign the request. Options Available: Complete, Resign</p>
<p><strong>STATUS: Complete</strong> - The request is finished. This is an end state. Not applicable to asset requests. Options Available: None</p>
<p><strong>STATUS: Accepted</strong> - The asset request is finished. This is an end state. Options Available: None</p>
<p><strong>STATUS: Cancel</strong> - Processor has canceled the request. This is an end state. Options Available: None</p>
<p><strong>STATUS: Reject</strong> - Processor has rejected the request. This is an end state. Options Available: None</p>
<p><strong>STATUS: Resigned</strong> - The processor has resigned on a new purchase because signed confirmation documents were never received from the sponsor. This is an end state. Options Available: None</p>
<h1 id="innotrust-integration">Innotrust Integration</h1>
<p>AAA writes to Innotrust when requests enter PROCESSING status.</p>
<h2 id="asset-sponsors-1">Asset Sponsors</h2>
<p>When asset sponsors are created or updated, the information is sent to Innotrust. It creates or updates a “contact” record for the sponsor and their info. Individuals added to an asset or asset sponsor are not sent to Innotrust as actual contacts. Information for these individuals is added, updated, and deleted solely within AAA.</p>
<h2 id="assets-1">Assets</h2>
<p>When an asset is accepted and enters its final state, then its information (name, price, CUSIP) is sent to Innotrust to create a “security” record. The asset is also connected to the asset sponsor contact.</p>
<h2 id="client-requests">Client Requests</h2>
<p>When a client request enters PROCESSING status, then its information is sent to Innotrust to create “transaction,” which vary slightly according to the request type:</p>
<ul>
<li>New and Additional Purchases send out money (check or wire) and add shares to the client’s account.</li>
<li>Capital Calls send out money (check or wire)</li>
<li>Exchanges remove shares of one asset and add shares of another.</li>
</ul>
<h3 id="note-about-safe-agreements-and-convertible-notes">Note about SAFE Agreements and Convertible Notes</h3>
<p>Because requests for SAFE and CN asset types require extra paperwork and are beyond the initial scope of AAA, such requests must be processed manually in Innotrust.</p>

