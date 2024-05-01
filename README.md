# MultiFrameworksProblem1
Minimal reproduceable example of an issue with trying to target multiple frameworks in .Net6 and .Net Framework 4.8

This works BETTER, in that during runtime it chooses the correct dependency. But it still has an oddity in Visual Studio where the 'path' property for the DependencyMulti project shows the .net6-windows dll in the Consumer48 solution.