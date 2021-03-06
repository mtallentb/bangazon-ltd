# Classes

## Setup

```
mkdir -p ~/workspace/ruby/exercises/classes && cd $_
touch employees.rb
```

## Instructions

1. Create a class that contains information about employees of a company and define methods to get/set employee name, job title, and start date.

2. Copy this `Company` class into your module.

    ```
    class Company
        #This represents a company in which people work

        def initialize(self, name, title, start_date):
            @name = name
            @title = title
            @start_date = start_date
        end

        def name
            #Returns the name of the company
            @name
        end

        # Add the remaining methods to fill the requirements above
    end
    ```

3. Consider the concept of [aggregation](../FND_11_INHERIT_COMPOSE_AGGREGATE.md#aggregation), and modify the `Company` class so that you assign employees to a company.
4. Create a company, and three employees, and then assign the employees to the company.
