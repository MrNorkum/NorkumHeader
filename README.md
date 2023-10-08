# 42header Kurulumu
C projeleri için zorunlu olan header'ı bu doküman ve dosyalar yardımıyla kurabilirsiniz.<br>
```vim
/* ************************************************************************** */
/*                                                                            */
/*                                                        :::      ::::::::   */
/*   ft_norkum.c                                        :+:      :+:    :+:   */
/*                                                    +:+ +:+         +:+     */
/*   By: norkum <norkum@student.42kocaeli.com.tr>   +#+  +:+       +#+        */
/*                                                +#+#+#+#+#+   +#+           */
/*   Created: 2004/06/29 xx:xx:xx by norkum            #+#    #+#             */
/*   Updated: 2023/10/08 12:06:49 by norkum           ###   ########.tr       */
/*                                                                            */
/* ************************************************************************** */
```

# Kurulum Adımları
1-) GitHub'da bulunan bu dosyaları bilgisayarınıza çekmek için sağ üst tarafta bulunan `Code` yazısına tıkladıktan sonra oradaki linki kopyalayın.<br>
2-) Terminali açın ve masaüstüne gelin<br>
3-) Terminale `git clone (link)` komutunu girin ve dosyaları indirin<br>
4-) İndirdiğiniz klasörün içine girin<br>
5-) Terminalden `sh create_header.sh` komutu ile shell dosyasını çalıştırın<br>
6-) Terminale `cd` komutunu yazarak root'a dönün<br>
7-) Terminale  `vim .vimrc` komutunu girin<br>
8-) Açılan boş sayfaya altta bulunan değerleri yazın

------------

    syntax on
    :set number
    let g:user42 = 'kullaniciAdi'
    let g:mail42 = 'kullaniciAdi@student.42kocaeli.com.tr'

------------

10-) İşlemi tamamladıktan sonra `:wq` komutu ile terminalden çıkın<br>
11-) Yeni oluşturduğunuz dosyalara header'ınızı çekmek için `:Baslik` yazıp enterlamalısınız.
