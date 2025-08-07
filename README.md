# Ideas
situaciónes modulares de bajo costo
import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { BadgeCheck, Building2, Users, Globe, Home, School, Briefcase } from "lucide-react";

export default function ModularHomePage() {
  return (
    <main className="min-h-screen bg-white text-gray-800 p-6 space-y-12">
      <section className="text-center space-y-4">
        <h1 className="text-4xl font-bold">Viviendas Modulares Mexicanas</h1>
        <p className="text-lg max-w-2xl mx-auto">
          Soluciones inteligentes, sostenibles y accesibles: viviendas, oficinas, aulas, clínicas, casetas y más.
        </p>
        <Button className="text-lg px-6 py-3 rounded-2xl">Contáctanos</Button>
      </section>

      <section className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <Card>
          <CardContent className="p-6 space-y-3">
            <Building2 className="w-10 h-10" />
            <h2 className="text-xl font-semibold">¿Por qué construcción modular?</h2>
            <ul className="list-disc list-inside text-gray-700">
              <li>Instalación rápida</li>
              <li>Bajo costo</li>
              <li>Diseños personalizables</li>
              <li>Ecoeficiente y sostenible</li>
            </ul>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-6 space-y-3">
            <Users className="w-10 h-10" />
            <h2 className="text-xl font-semibold">Impacto social</h2>
            <ul className="list-disc list-inside text-gray-700">
              <li>Reducción del déficit habitacional</li>
              <li>Generación de empleos locales</li>
              <li>Educación y salud en zonas rurales</li>
              <li>Vivienda digna para migrantes</li>
            </ul>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-6 space-y-3">
            <Globe className="w-10 h-10" />
            <h2 className="text-xl font-semibold">Alcance internacional</h2>
            <p className="text-gray-700">
              Exportamos a EE.UU., Centroamérica y el Caribe. Aprovechamos la ubicación estratégica de México y los beneficios del T-MEC.
            </p>
          </CardContent>
        </Card>
      </section>

      <section className="py-12 space-y-10">
        <h2 className="text-3xl font-bold text-center">Ejemplos de Aplicación</h2>
        <div className="grid grid-cols-1 md:grid-cols-3 gap-6">
          <Card>
            <CardContent className="p-6 space-y-3 text-center">
              <Home className="w-10 h-10 mx-auto" />
              <h3 className="text-xl font-semibold">Casas de interés social</h3>
              <p className="text-gray-700">Viviendas asequibles, listas en días, ideales para comunidades rurales o urbanas.</p>
            </CardContent>
          </Card>

          <Card>
            <CardContent className="p-6 space-y-3 text-center">
              <Briefcase className="w-10 h-10 mx-auto" />
              <h3 className="text-xl font-semibold">Oficinas móviles</h3>
              <p className="text-gray-700">Soluciones para parques industriales, zonas remotas o necesidades temporales de empresas.</p>
            </CardContent>
          </Card>

          <Card>
            <CardContent className="p-6 space-y-3 text-center">
              <School className="w-10 h-10 mx-auto" />
              <h3 className="text-xl font-semibold">Aulas escolares</h3>
              <p className="text-gray-700">Espacios educativos listos para usarse, ideales para zonas afectadas o con falta de infraestructura.</p>
            </CardContent>
          </Card>
        </div>
      </section>

      <section className="text-center py-12 space-y-4">
        <h2 className="text-3xl font-bold">Únete a la revolución modular</h2>
        <p className="max-w-xl mx-auto text-gray-600">
          Estamos construyendo el futuro, un módulo a la vez. ¿Eres desarrollador, ONG, gobierno o inversionista? Queremos escucharte.
        </p>
        <Button className="text-lg px-6 py-3 rounded-2xl">Solicita más información</Button>
      </section>

      <footer className="text-center text-sm text-gray-500 pt-12">
        © 2025 Viviendas Modulares Mexicanas · Emilio Alarcón y Jose Pablo Michel · 
      </footer>
    </main>
  );
}
