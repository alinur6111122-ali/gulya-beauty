# GULYA BEAUTY — APK hazırlamaq

Bu qovluq Android Studio layihəsidir. APK faylı hazır deyil; GitHub Actions vasitəsilə avtomatik yığılır.

## Ən asan üsul: GitHub ilə APK yaratmaq

1. https://github.com saytına daxil olun və hesabınıza girin.
2. `+` düyməsi → **New repository** seçin.
3. Repository name: `gulya-beauty` yazın. **Private** seçə bilərsiniz. **Create repository** basın.
4. Bu qovluğun İÇİNDƏKİ bütün fayl və qovluqları GitHub-da **Add file → Upload files** ilə yükləyin. Vacibdir: `.github` qovluğu da yüklənməlidir.
5. Aşağıda **Commit changes** basın.
6. Repository-də **Actions** bölməsinə keçin. `Build GULYA BEAUTY APK` adlı prosesi açın.
7. Yaşıl işarə ilə tamamlananda həmin prosesə daxil olun, aşağıdakı **Artifacts** hissəsində `GULYA-BEAUTY-APK` faylını endirin.
8. Endirdiyiniz ZIP-i açın. İçində `app-debug.apk` olacaq. APK-nı Android telefona göndərin və quraşdırın.

## Qeyd
- Bu layihə Android Studio / GitHub Actions ilə Android APK yığmaq üçündür.
- APK debug imzası ilə hazırlanır; şəxsi test və quraşdırma üçündür.
- GitHub hesabına giriş və internet lazımdır.
- GitHub hesabınızın Actions istifadəsinə dair limitləri ola bilər.
- APK yaradıldıqdan sonra onu telefonda quraşdırarkən Android naməlum mənbədən quraşdırma icazəsi istəyə bilər.
