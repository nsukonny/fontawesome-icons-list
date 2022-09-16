# fontawesome-icons-list
The list of fontawesome icons in JSON.


Example by:
```
$file = file_get_contents('fontawesome-6-free.json');
$icons = json_decode($file, true);
```
you will get 

```
Array
(
    [0] => Array
        (
            [icon] => fa-solid fa-house fa-fw
            [name] => house
        )

    [1] => Array
        (
            [icon] => fa-solid fa-magnifying-glass fa-fw
            [name] => magnifying-glass
        )

    [2] => Array
        (
            [icon] => fa-solid fa-user fa-fw
            [name] => user
        )
        .......
    [2015] => Array
        (
            [icon] => fa-regular fa-bell-slash fa-fw
            [name] => bell-slash
        )

)
```
