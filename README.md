
#[ngClass] directive --<div [ngClass]="'text-white p-3 ' +getClasses()">
 one way databinding için bir örnek oluşturduk
  amacımız component.ts dosyasında oluşturduğumuz bir method veya properties içerisindeki değeri tek taraflı olarak ekrana yansıtırız.
 # if conditional operator
      return this.model.getProducts().length=== 5? "bg-success":"bg-danger";
  if kontrolü yapılmakta olup doğru ise  yeşil değilse kırmızı yapar zemin rengi 
  # property binding
   <input class="form-control" [value]="model.getProduct(20)?.name?? 'DEĞER BULUNAMADI'"
          null contidional operatör ile eğer ilgili kayıt varsa onun namini geitirir yoksa null yerine bulunamdı bilgisni geçer
          
  
  
