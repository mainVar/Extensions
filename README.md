
# Сhain expresion for Unity

Сhain expression body exemlp code

    
        testObject.With(o => o.transform.position = new Vector3(1f, 1f, 1f))  // do some staf
            .With(o => o.transform.Rotate(new Vector3(0f, 90f, 0f)), () => testObject != null) // do some staf if it true by method
            .With(o => o.transform.localScale = new Vector3(2f, 2f, 2f), testObject != null); // do some staf if expression left are true
   




