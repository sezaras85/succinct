Succinct Labs,  özellikle **zero-knowledge proof (zk-proof)** teknolojileri üzerine odaklanan bir araştırma ve geliştirme şirketidir. Projeleri, blok zincirler arası iletişimi (cross-chain communication) ve ölçeklenebilirliği artırmayı hedefler. Succinct Labs, zk-proof'ları kullanarak hem güvenli hem de verimli çözümler sunmayı amaçlar.

#### Succinct Labs'ın Odaklandığı Alanlar:
1. **Zero-Knowledge Proofs (zk-Proofs):**
   - Gizlilik ve ölçeklenebilirlik sağlayan zk-proof teknolojileri üzerine çalışmalar yapıyor.
   - Bu teknoloji, blok zincirlerdeki işlemlerin doğrulanmasını hızlandırırken, maliyetleri de düşürüyor.

2. **Cross-Chain Communication:**
   - Farklı blok zincirleri arasında güvenli ve hızlı iletişim sağlayan çözümler geliştiriyor.
   - Bu, token transferleri ve veri paylaşımı için önemli bir altyapı sunar.

3. **Developer Tools:**
   - Geliştiriciler için zk-proof tabanlı araçlar ve kütüphaneler sağlayarak, yeni uygulamaların oluşturulmasını kolaylaştırıyor.


Bir developer iseniz aşağıdaki yer alan kodlarla ubuntu üzerinden bir anahtar çifti oluşturarak Succinct Prover Network Beta'ya başvurabilirsiniz.


```markdown

## Kurulum

Projeyi başlatmak için aşağıdaki adımları izleyin.

### Gereksinimler

- Ubuntu veya benzeri bir Linux dağıtımı
- `sudo` yetkileri

### Adım 1: Sistem Güncellemeleri ve Temel Paketlerin Kurulumu

Öncelikle sisteminizi güncelleyin ve gerekli paketleri kurun:

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install build-essential git curl gcc make jq clang protobuf-compiler pkg-config libssl-dev -y
```

### Adım 2: Rust Kurulumu

Rust'ı kurmak için aşağıdaki komutları çalıştırın:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source ~/.profile
source ~/.cargo/env
```

### Adım 3: SP1 Kurulumu

SP1'ı kurmak için aşağıdaki komutları çalıştırın:

```bash
curl -L https://sp1up.succinct.xyz | bash
source /root/.bashrc
sp1up
```

### Adım 4: Foundry Kurulumu

Foundry'yi kurmak için aşağıdaki komutları çalıştırın:

```bash
curl -L https://foundry.paradigm.xyz | bash
source /root/.bashrc
foundryup
```

### Adım 5: Yeni Cüzdan Oluşturma

Yeni bir cüzdan oluşturmak için aşağıdaki komutu kullanın:

```bash
cast wallet new
```

**Not:** Özel anahtarınızı asla kaybetmeyin veya paylaşmayın.

### Adım 6: Cüzdan Kurtarma (İsteğe Bağlı)

Eğer cüzdanınızı kurtarmanız gerekiyorsa, aşağıdaki komutu kullanın:

```bash
cast wallet address --private-key PRIV
```

`PRIV` yerine özel anahtarınızı yazın.

## Kullanım

Projeyi kullanmaya başlamak için gerekli tüm kurulum adımlarını tamamladıktan sonra, proje dosyalarınızı düzenleyebilir ve geliştirmeye başlayabilirsiniz.

En son adım olarak aşağıdaki formda gerekli alanları doldurarak gönderebilirsiniz:

https://docs.google.com/forms/d/e/1FAIpQLSd-X9uH7G0bvXH_kjptnQtNil8L4dumrVPpFE4t8Ci1XT1GaQ/viewform


