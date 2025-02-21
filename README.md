```markdown
# Succinct Labs Token Projesi

Bu proje, Succinct Labs tarafından geliştirilen bir token projesidir. Aşağıda projenin kurulum ve kullanım adımları bulunmaktadır.

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

## Katkıda Bulunma

Eğer bu projeye katkıda bulunmak isterseniz, lütfen aşağıdaki adımları izleyin:

1. Bu repoyu fork edin.
2. Yeni bir branch oluşturun (`git checkout -b feature/AmazingFeature`).
3. Değişikliklerinizi commit edin (`git commit -m 'Add some AmazingFeature'`).
4. Branch'inizi pushlayın (`git push origin feature/AmazingFeature`).
5. Bir Pull Request açın.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakın.

---

**Not:** Bu belge, projenin temel kurulum adımlarını içermektedir. Projenin geliştirilmesi sırasında bu adımlar güncellenebilir.
```
