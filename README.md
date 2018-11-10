# Seleksi-Grand-Bootcamp-Arkademy
Ahmad Julius Tarigan
Medan
1.
{
"itemId" : "12341822",
"itemName" : "basic_t-shirt",
"price" : "70000",
"ColorAndSize" : [
	{"Color":"Red", "Size":["S,M,L"]},
	{"Color":"solid_Black", "Size":["M,L"]},
]
freeShiping : "false",
}

2.
<script type="text/javascript">
function validasi_input(form){
   pola_username=/^[a-z]{5,100}$+_.[A-Z]{2,100}/;
   if (!pola_username.test(form.username.value)){
      alert ('Salah');
      form.username.focus();
      return false;
   }
return (true);
}
</script>

3.
#include <iostream>
using namespace std;
void awal(){
  int i,j,n;
    cout<<"######Maks 10 Deret######"<<endl;
    cout<<"Panjang Deret : ";
    cin>>n;
    if(n>10){
	 cout<<"######Out of Range######"<<endl;
	 awal();
	 }
	 else{
	cout<<"Segitiga("<<n<<")"<<endl;
     for (i=1;i<=n;i++) {
        for (j=1;j<=i;j++) 
             cout<<j<<", ";
             cout<<endl;
    }}}
int main() {
awal();
return 0;

4.
#include <iostream>
using namespace std;
int main() {
    int a,j;
	cout<<"Jumlah Jabat Tangan :";
	cin>>a;
    j=0.5*(a*(a-1));
    cout<<j<<endl;
        return 0;
}
