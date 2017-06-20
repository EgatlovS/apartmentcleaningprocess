# apartmentcleaningprocess

Just played around with some parallel gateways!

## Parallel Gateway
> A parallel gateway does'nt mean your process is multithreaded when reaching it.
> It just means your splitting the token.
> The converging one just waits until each incoming sequenceflow shipped a token and synchronizes
> them afterwards.
> !Note!
> If conditions are defined on the sequence flow connected with the parallel gateway,
> they are simply ignored

***

## bpmn model
![apartmentcleaningprocess](http://i.imgur.com/YPDXpO6.png)

***

### Stuff used to make this:
 * [camunda modeling reference](https://camunda.org/bpmn/reference/#gateways-data-based-exclusive-gateways)
 * [camunda docs](https://docs.camunda.org/manual/7.6/reference/bpmn20/gateways/exclusive-gateway/)
 * [camunda github](https://github.com/camunda/)
 * [camunda modeler](https://camunda.org/download/modeler/)
 * [camunda wildfly distribution](https://camunda.org/download/)
