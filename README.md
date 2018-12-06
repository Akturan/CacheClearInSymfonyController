# Symfony:Cache clear command in controller
Using cache clear command in symfony controller action method
```PHP
$input = new \Symfony\Component\Console\Input\ArgvInput(array('console','cache:clear'));
$application = new \Symfony\Bundle\FrameworkBundle\Console\Application($this->get('kernel'));
$application->run($input);```
