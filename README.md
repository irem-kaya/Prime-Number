# Prime Number

Bu proje, asal sayıların hesaplanması ve kontrol edilmesi amacıyla geliştirilmiş bir Python uygulamasıdır. Kullanıcılar, belirli bir aralıktaki asal sayıları bulabilir veya bir sayının asal olup olmadığını kontrol edebilirler.

## İçindekiler

- [Özellikler](#özellikler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Sınıf Detayları](#sınıf-detayları)
- [Katkıda Bulunma](#katkıda-bulunma)
  

## Özellikler

- Belirli bir aralıktaki asal sayıları hesaplama
- Bir sayının asal olup olmadığını kontrol etme


## Kurulum

Projeyi yerel makinenize kurmak için aşağıdaki adımları izleyin:

1. Bu projeyi klonlayın:
    ```bash
    git clone https://github.com/irem-kaya/Prime-Number.git
    ```

2. Proje dizinine gidin:
    ```bash
    cd Prime-Number
    ```

3. Gerekli bağımlılıkları yükleyin (varsa):
    ```bash
    pip install -r requirements.txt
    ```

## Kullanım

Projeyi çalıştırmak için aşağıdaki adımları izleyin:

1. Ana dosyayı çalıştırın:
    ```bash
    python main.py
    ```

2. Program başlatıldığında, kullanıcı arayüzü üzerinden asal sayıları hesaplayabilir veya bir sayının asal olup olmadığını kontrol edebilirsiniz.

### Örnek Kullanım

```python
from prime_number import PrimeNumber

# PrimeNumber sınıfını oluşturma
prime = PrimeNumber()

# Belirli bir aralıktaki asal sayıları hesaplama
prime_numbers = prime.find_primes_in_range(1, 100)
print(prime_numbers)

# Bir sayının asal olup olmadığını kontrol etme
is_prime = prime.is_prime(29)
print(is_prime)
