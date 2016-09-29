unifiler
====
![rini](rini.png)
<br>
유니티 퍼포먼스 프로파일러<br>
![cg](cg.png)
<br>
```cs
    public void Update()
    {
        Debug.Log("A");

        Bar(1, 2);

        Zoo();

        UnityEngine.Debug.Log("DEBUG");
    }
    public void Zoo()
    {
        Rini();
        Rini();
    }
    public void Rini()
    {
        UnityEngine.Debug.Log("DEBUG");
    }
```

