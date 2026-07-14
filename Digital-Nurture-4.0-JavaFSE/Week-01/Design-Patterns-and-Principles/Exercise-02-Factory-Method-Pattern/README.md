# Factory Method Document Creator

## About the Exercise
In this exercise, I worked on the Factory Method design pattern. Different document objects are created through their corresponding factory classes.

## Files
* `Document.java` – Common document interface
* `DocumentFactory.java` – Abstract factory creator class
* `ExcelDocument.java` – Excel document format implementation
* `ExcelDocumentFactory.java` – Factory for generating Excel document instances
* `FactoryMethodTest.java` – Tests verifying documents are instantiated using Factory methods
* `PdfDocument.java` – PDF document format implementation
* `PdfDocumentFactory.java` – Factory for generating PDF document instances
* `pom.xml` – Maven file containing dependencies and build settings
* `WordDocument.java` – Word document format implementation
* `WordDocumentFactory.java` – Factory for generating Word document instances

## My Approach
A common document interface is implemented by different document types. Factory classes are responsible for creating the required objects.

## How to Run
```bash
mvn clean test
```

## Output
The test uses Word, PDF, and Excel factories to instantiate and trigger document operations.

## What I Understood
I learned how factory classes reduce direct object creation and make the program easier to extend.
