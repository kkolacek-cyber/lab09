using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace NotesApp {
    class Baza {
        public static string KonekcijskiString() {
            string server = Environment.GetEnvironmentVariable("DB_SERVER") ?? "sql.vub.zone,14330";
            string baza = Environment.GetEnvironmentVariable("DB_DATABASE") ?? "Baza1";
            string korisnickoIme = Environment.GetEnvironmentVariable("DB_USER") ?? "sa";
            string lozinka = Environment.GetEnvironmentVariable("DB_PASSWORD") ?? "yFxr3yPRxhc7iOvS8K6ZP2XkBEiP";

            return string.Format(
                "Data Source = {0}; Initial Catalog = {1}; User ID = {2}; Password = {3}",
                server,
                baza,
                korisnickoIme,
                lozinka
            );
        }
    }
}
