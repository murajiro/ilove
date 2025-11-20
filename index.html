import React, { useState } from 'react';
import { Heart, Volume2 } from 'lucide-react';

export default function LoveLanguages() {
  const [playingId, setPlayingId] = useState(null);

  const languages = [
    { id: 1, country: 'Brasil', flag: '🇧🇷', text: 'Eu te amo', lang: 'pt-BR', colors: 'from-green-500 to-yellow-400', audio:'Audios/Brasil.m4a' },
    { id: 2, country: 'Estados Unidos', flag: '🇺🇸', text: 'I love you', lang: 'en-US', colors: 'from-blue-600 to-red-600', audio: 'Audios/Estados Unidos.m4a' },
    { id: 3, country: 'Espanha', flag: '🇪🇸', text: 'Te amo', lang: 'es-ES', colors: 'from-red-600 to-yellow-400', audio: 'Audios/Espanha.m4a' },
    { id: 4, country: 'França', flag: '🇫🇷', text: 'Je t\'aime', lang: 'fr-FR', colors: 'from-blue-600 to-red-600', audio: 'Audios/Franc¦ºa.m4a' },
    { id: 5, country: 'Itália', flag: '🇮🇹', text: 'Ti amo', lang: 'it-IT', colors: 'from-green-500 to-red-600', audio: 'Audios/Ita¦ülia.m4a' },
    { id: 6, country: 'Alemanha', flag: '🇩🇪', text: 'Ich liebe dich', lang: 'de-DE', colors: 'from-yellow-400 to-red-600', audio:'Audios/Alemanha.m4a' },
    { id: 7, country: 'Japão', flag: '🇯🇵', text: '愛してる', lang: 'ja-JP', colors: 'from-red-500 to-white', audio: 'Audios/Japa¦âo.m4a' },
    { id: 8, country: 'Coreia', flag: '🇰🇷', text: '사랑해', lang: 'ko-KR', colors: 'from-blue-500 to-red-500', audio: 'Audios/Coreia.m4a' },
    { id: 9, country: 'China', flag: '🇨🇳', text: '我爱你', lang: 'zh-CN', colors: 'from-red-600 to-yellow-400', audio: 'Audios/China.m4a' },
    { id: 10, country: 'Rússia', flag: '🇷🇺', text: 'Я люблю тебя', lang: 'ru-RU', colors: 'from-blue-600 to-red-600', audio: 'Audios/Ru¦üssia.m4a' },
    { id: 11, country: 'Grécia', flag: '🇬🇷', text: 'Σ\'αγαπώ', lang: 'el-GR', colors: 'from-blue-500 to-white', audio: 'Audios/Gre¦ücia.m4a' },
    { id: 12, country: 'Índia', flag: '🇮🇳', text: 'मैं तुमसे प्यार करता हूँ', lang: 'hi-IN', colors: 'from-orange-500 to-green-600', audio: 'Audios/Indone¦üsia.m4a' },
    { id: 13, country: 'Portugal', flag: '🇵🇹', text: 'Amo-te', lang: 'pt-PT', colors: 'from-green-600 to-red-600', audio: 'Audios/Portugal.m4a' },
    { id: 14, country: 'Holanda', flag: '🇳🇱', text: 'Ik hou van je', lang: 'nl-NL', colors: 'from-red-600 to-blue-600', audio: 'Audios/Holanda.m4a'},
    { id: 15, country: 'Suécia', flag: '🇸🇪', text: 'Jag älskar dig', lang: 'sv-SE', colors: 'from-blue-500 to-yellow-400', audio: 'Audios/Sue¦ücia.m4a' },
    { id: 17, country: 'Polônia', flag: '🇵🇱', text: 'Kocham cię', lang: 'pl-PL', colors: 'from-white to-red-600', audio: 'Audios/Polonia.m4a' },
    { id: 18, country: 'Turquia', flag: '🇹🇷', text: 'Seni seviyorum', lang: 'tr-TR', colors: 'from-red-600 to-white', audio: 'Audios/Turquia.m4a' },
    { id: 19, country: 'Tailândia', flag: '🇹🇭', text: 'ฉันรักคุณ', lang: 'th-TH', colors: 'from-red-600 to-blue-600', audio: 'Audios/Taila¦éndia.m4a' },
    { id: 20, country: 'Vietnã', flag: '🇻🇳', text: 'Anh yêu em', lang: 'vi-VN', colors: 'from-red-600 to-yellow-400', audio: 'Audios/Vietna¦â.m4a' },
    { id: 21, country: 'Indonésia', flag: '🇮🇩', text: 'Aku cinta kamu', lang: 'id-ID', colors: 'from-red-600 to-white', audio: 'Audios/Indone¦üsia.m4a' },
    { id: 22, country: 'Filipinas', flag: '🇵🇭', text: 'Mahal kita', lang: 'fil-PH', colors: 'from-blue-500 to-red-600', audio: 'Audios/Filipinas.m4a'},
    { id: 23, country: 'Argentina', flag: '🇦🇷', text: 'Te amo', lang: 'es-AR', colors: 'from-blue-400 to-yellow-300', audio: 'Audios/Argentina.m4a' },
    { id: 24, country: 'México', flag: '🇲🇽', text: 'Te amo', lang: 'es-MX', colors: 'from-green-600 to-red-600', audio: 'Audios/Me¦üxico.m4a' },
  ];

  const speak = (text, lang, id, audioUrl) => {
    // Se tiver áudio personalizado, toca ele
    if (audioUrl) {
      const audio = new Audio(audioUrl);
      setPlayingId(id);
      audio.play();
      audio.onended = () => setPlayingId(null);
      return;
    }

    // Senão, usa o sintetizador de voz
    if ('speechSynthesis' in window) {
      window.speechSynthesis.cancel();
      
      const utterance = new SpeechSynthesisUtterance(text);
      utterance.lang = lang;
      utterance.rate = 0.9;
      utterance.pitch = 1;
      
      setPlayingId(id);
      
      utterance.onend = () => {
        setPlayingId(null);
      };
      
      window.speechSynthesis.speak(utterance);
    }
  };

  return (
    <div className="min-h-screen bg-gradient-to-br from-pink-100 via-purple-50 to-red-100 p-4 pb-8">
      <div className="max-w-md mx-auto">
        {/* Header */}
        <div className="text-center py-8 mb-6">
          <div className="flex justify-center mb-4">
            <Heart className="w-16 h-16 text-red-500 fill-red-500 animate-pulse" />
          </div>
          <h1 className="text-3xl font-bold text-gray-800 mb-2">
            Para Você, Meu Amor
          </h1>
          <p className="text-gray-600">
            Toque nas bandeiras para ouvir ❤️
          </p>
        </div>

        {/* Languages Grid */}
        <div className="grid grid-cols-2 gap-4">
          {languages.map((item) => (
            <button
              key={item.id}
              onClick={() => speak(item.text, item.lang, item.id, item.audio)}
              className={`relative overflow-hidden rounded-2xl p-6 shadow-lg hover:shadow-xl transform hover:scale-105 transition-all duration-300 ${
                playingId === item.id ? 'ring-4 ring-red-400 scale-105' : ''
              }`}
            >
              {/* Gradient Background */}
              <div className={`absolute inset-0 bg-gradient-to-br ${item.colors} opacity-20`}></div>
              
              {/* Content */}
              <div className="relative">
                <div className="text-6xl mb-3">{item.flag}</div>
                <div className="text-sm font-semibold text-gray-800 mb-1">
                  {item.country}
                </div>
                <div className="text-xs text-gray-600 mb-2">{item.text}</div>
                {playingId === item.id && (
                  <Volume2 className="w-4 h-4 text-red-500 mx-auto animate-pulse" />
                )}
              </div>
            </button>
          ))}
        </div>

        {/* Footer */}
        <div className="text-center mt-8 p-6 bg-white/50 rounded-2xl backdrop-blur-sm">
          <p className="text-gray-700 italic">
            "Em qualquer idioma, meu amor por você é o mesmo"
          </p>
          <div className="flex justify-center gap-2 mt-3">
            <Heart className="w-4 h-4 text-red-500 fill-red-500" />
            <Heart className="w-4 h-4 text-red-500 fill-red-500" />
            <Heart className="w-4 h-4 text-red-500 fill-red-500" />
          </div>
        </div>
      </div>
    </div>
  );
}
