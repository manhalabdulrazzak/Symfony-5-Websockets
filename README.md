# Symfony-5-Websockets

###### Symfony 5 Websockets Example chat app testing !




##### To install it, type the following in your terminal:

`composer require cboden/ratchet`

# **Note:** 
Note:
As of this writing,
the pull request https://github.com/ratchetphp/Ratchet/pull/766
to update RatchetPHP for Symfony 5 hasn’t been merged in yet. However it is passing all tests. If you are looking to use this in production, I would wait until it’s been merged in. But if you’re just here to learn, then it’s fine to use as is.
To use the branch that has the Symfony 5 update, you’ll need to add the following to your composer.json file:

``"repositories":[{
    "type": "vcs",
    "url": "https://github.com/simPod/Ratchet.git"
}],`
``

This will add the forked repo with the Symfony 5 fix of the Ratchet library. Adding this allows us to use composer to install the branch with the fix.

`{
    "type": "project",
    "license": "proprietary",
    "repositories": [{
        "type": "vcs",
        "url": "https://github.com/simPod/Ratchet.git"
    }],
    "require": {
        "php": "^7.2.5",
        "ext-ctype": "*",
        "ext-iconv": "*",
        "symfony/console": "5.0.*",
        "symfony/dotenv": "5.0.*",`
        




Next you will need to install the library using the specific fixed branch. To do that type in your terminal:


`composer require cboden/ratchet:dev-allow-symfony-5
`

And that should install without any errors.

Type the following to install those:

`composer require twig
`

`composer require annotations
`

`composer require symfony/maker-bundle --dev
`



raed here for more : 
https://rojas.io/symfony-5-websockets-tutorial/

