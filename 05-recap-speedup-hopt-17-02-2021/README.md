Экспериментировать будем на CIFAR10. Лучше скачать его заранее. Для этого создайте папку для семинара, из неё выполните:
python3 -c 'import torchvision;torchvision.datasets.CIFAR10("data", download=True, train=True);torchvision.datasets.CIFAR10("data", download=True, train=False)'
