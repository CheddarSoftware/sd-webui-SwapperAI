# Swapper AI Stable Diffusion Eklentisi

Bu eklenti, StableDiffusion'da [AUTOMATIC1111 web-ui](https://github.com/AUTOMATIC1111/stable-diffusion-webui/) yüz değiştirmeyi sağlar. Bu eklenti [Swapper AI](https://github.com/CheddarSoftware/Swapper-AI) temel alınarak oluşturuldu.

## Kurulum

> Windows için [Visual Studio](https://visualstudio.microsoft.com/downloads/) indirip yüklemeniz gerekir. Kurulum sırasında C++ paketini ve Python'u eklediğinizden emin olun.
+ Bu komutu çalıştırın: `pip install insightface==0.7.3`
+ Web-UI'da "Extensions" sekmesine gidin ve `https://github.com/CheddarSoftware/sd-webui-SwapperAI` bağlantısını "install from URL" sekmsine eklyip kurulumu başlatın.
+ Web-UI'ı kapatın ve yeniden başlatın.

## Kullanım

1. "Swapper AI" sekmesi altında, yüz içeren bir görüntüyü içe aktarın.
2. "Enable" onay kutusunu aktif hale getirin.
3. Görüntünün işlenmesini bekleyin.

## Öneriler

#### Kaliteli sonuçlar elde etme

Her şeyden önce, "Yüzü Geliştir" seçeneğinin etkinleştirildiğinden emin olun. Ayrıca "Upscaler" seçeneğini deneyebilir veya daha hassas kontrol için "Extras" sekmesinden bir upscaler kullanabilirsiniz.

Daha iyi kalite için, img2img'in "Denoising strength" ayarını "0,1" olarak kullanın ve kalite ile benzerlik arasında bir denge elde edene kadar kademeli olarak artırın.

#### Belirli yüzleri değiştirme
Bir görüntüde birden fazla yüz varsa, "Virgülle ayrılmış yüz numaraları" seçeneğini kullanarak değiştirmek istediğiniz yüz numaralarını seçin. (0'dan başlar)
