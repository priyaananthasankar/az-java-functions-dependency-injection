# Azure Java Functions Dependency Injection

## Reference

Azure Repos

https://github.com/Azure/azure-functions-java-worker/issues/324
https://github.com/Azure/azure-functions-java-worker/pull/318/files

## Scenarios

- Be able to use Quarkus CDI for Java Azure Functions Dependency Injection (Learning)
- Inject Azure Services by default, like Logging and Telemetry through App Insights (makes the code idiomatic to Java developer).
- Inject Unit Testing like PowerMock, Mockito and Junit Mock.
- Inject Custom Services like common utilities - if custom utility is built, it should be injectable, eg: custom exception handling, logging, validation
  eg: Be able to inject MongoDB dependency as explained in the problem [here](https://stackoverflow.com/questions/60548438/dependency-injection-ioc-in-java-azure-functions)
  
## Benefits

- Dependency Injection is a paradigm that is idiomatic to Java Developers and currently only C# is a first citizen of this benefit.

## Outcomes

- Clear design on how to address native dependency injection in Azure Function (without custom Startup classes) 
