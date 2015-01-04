Zorbus User Theme Bundle
========================

This bundle provides a theme for the [SonataUserBundle](http://sonata-project.org/bundles/user/master/doc/reference/installation.html)

Just add to composer and enable the bundle on AppKernel and you are ready to go.

The bundle overrides all the templates bu setting the SonataUserBundle as its parent.

```php
public function registerBundles()
{
    $bundles = array(
        ...,
        new Zorbus\UserThemeBundle\ZorbusUserThemeBundle(),
    );
}
```