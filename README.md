-To train PYTORCH-DDP:    
```
python train-multi-ddp.py --net_type pyramidnet --dataset cifar100 --depth 200 --alpha 240 --batch_size 512 --lr 0.25 --expname PyraNet200 --epochs 1 --beta 1.0 --cutmix_prob 0.5 --dist-url 'tcp://localhost:10001' --multiprocessing-distributed --world-size 1 --rank 0
```
