## How to run

```bash
./xmrig -o randomxmonero.auto.nicehash.com:9200 -a rx -k -u <address_wallet>.bn01 -t 2
```

- -a: algorithm 
- .bn01: name of rig
- -t: number of cpu

## Run with notebook

Upload to drive `/content/drive/MyDrive/Colab/xmrig-6.21.3/xmrig`

```python
sh = """
chmod +x /content/drive/MyDrive/Colab/xmrig-6.21.3/xmrig
/content/drive/MyDrive/Colab/xmrig-6.21.3/xmrig -o randomxmonero.auto.nicehash.com:9200 -a rx -k -u NHbXpcyv1pQjjQsEEKch4xTe4Lg4hgStxd84.bn01 -t 8
"""
with open('script.sh', 'w') as file:
  file.write(sh)

!bash script.sh
```
