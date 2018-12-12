# Drupal 8 tricks

## Custom ```drupal_goto()```

``` 
function module_goto($path)
{
    $response = new RedirectResponse($path);
    $response->send();
    return $response;
} 
```
