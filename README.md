# KanbanViewProgressBarComponent

deploy component and use on page like :

<apex:page standardController="Opportunity" sidebar="false">   

  <c:ProgressBar UIElements="Prospecting,Qualification,Needs Analysis,Value Proposition,Id. Decision Makers,Perception Analysis,Proposal/Price Quote,Negotiation/Review,Closed Won,Closed Lost" StageName="Value Proposition"/>

</apex:page>

UIElements ==> all the stages name
StageName ==> current stage name