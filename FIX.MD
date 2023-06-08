## How to fix
The service "chartjs.twig_extension" has a dependency on a non-existent service "stimulus.helper".

## Solution
add to `config/bundles.php`
``Symfony\UX\StimulusBundle\StimulusBundle::class => ['all' => true],``

run `composer update`
