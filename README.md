# yii2-key-storage

```
"greg-repo/keystorage": {
	"type": "git",
	"url": "https://github.com/greg-repo/keystorage.git"
},
```

```
return [
	'vendorPath' => dirname(dirname(__DIR__)) . '/vendor',
	'components' => [
		...
	    'keyStorage' => [
		    'class' => 'keystorage\components\KeyStorage',
	    ],
	],
];
```