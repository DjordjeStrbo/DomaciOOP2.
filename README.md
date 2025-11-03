public abstract class Doktor {
    String ime;
    String specijalizacija;
    int godineIskustva;
    int brojPacijenata;
    int godinaDiplomiranja;

    public Doktor(String ime, int godineIskustva, int brojPacijenata, String specijalizacija, int godinaDiplomiranja) {
        this.ime = ime;
        this.godineIskustva = godineIskustva;
        this.brojPacijenata = brojPacijenata;
        this.specijalizacija = specijalizacija;
        this.godinaDiplomiranja = godinaDiplomiranja;
    }

    public Doktor(String ime, int godineIskustva) {
        this.ime = ime;
        this.godineIskustva = godineIskustva;
    }

    public Doktor(String ime) {
        this.ime = ime;
    }

    
    public abstract void leci();
}
